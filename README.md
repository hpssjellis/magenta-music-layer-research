# magenta-layer-research
Quick study of the effects different layers and training runs have on magenta Google's Tensorflow music generation Neural Network Program.



Jul22, 2016


Sorry, have not been keeping this readme.md file up to date.


I just re-organized the folder structure to include other builds with different number of midi files. I got magenta working on making it possible to re-train a run with a diffrerent set of midi files and have tested it.

https://groups.google.com/a/tensorflow.org/forum/#!topic/magenta-discuss/riVSW-dKJ3k




I also got magenta to set up a variable called temperature which allows some adjustment to the ability for a song to remember an exact song or something slightly different.

https://groups.google.com/a/tensorflow.org/forum/#!topic/magenta-discuss/SCZR9qrQUGM

I am presently testing this "temperature" variable.




# June 29, 2016

Clyp.it links for anyone who can't play online the github midi or mp3 files

# Inputs

[Rocksetta-Magenta-Research-input-1-a-few-of-my-favorite-things](https://clyp.it/gvz5zm1s)

[Rocksetta-Magenta-Research-input-2-god-rest-ye-merry-gentlemen](https://clyp.it/kq32hfdx)


# Primer

[Rocksetta-Magenta-Research-primer-fur-elise](https://clyp.it/4eiuopgx)





# Name format explained:

midi = number of inputs = 2 for this entire github repository

Layer = Tensorflow layers in the statement 

```
--hparams='{"rnn_layer_sizes":[50]}'
```
Could also be a 2 dimensional training neural network 
```
--hparams='{"rnn_layer_sizes":[30, 20]}'
```

Train = Number of training loops, note the defualt is to make a checkpoint and print data every 10 loops.


# All Research Outputs.

[Rocksetta-Magenta-Research-midi2-layer-2d-25-25-train300](https://clyp.it/hvwmwuuf)

[Rocksetta-Magenta-Research-midi2-layer-2d-5-5-train300](https://clyp.it/2dhmycye)

[Rocksetta-Magenta-Research-midi2-layer-2d-5-5-train1000](https://clyp.it/0nohxd40)

[Rocksetta-Magenta-Research-midi2-layer-2d-5-50-train300](https://clyp.it/mrrxf4nu)

[Rocksetta-Magenta-Research-midi2-layer-2d-50-5-train1000](https://clyp.it/meiefeop)

[Rocksetta-Magenta-Research-midi2-layer3-train20000](https://clyp.it/0vpjpwsw)

[Rocksetta-Magenta-Research-midi2-layer5-train300](https://clyp.it/nam41t5f)

[Rocksetta-Magenta-Research-midi2-layer5-train1000](https://clyp.it/ahn05ged)

[Rocksetta-Magenta-Research-midi2-layer-200-train1000](https://clyp.it/pa3tz0dh)

[Rocksetta-Magenta-Research-midi2-layer5-train1000](https://clyp.it/prydx2v4)

[Rocksetta-Magenta-Research-midi2-layer50-train300](https://clyp.it/lswzxuff)

[Rocksetta-Magenta-Research-midi2-layer50-train1000](https://clyp.it/h3sxnrwc)

[Rocksetta-Magenta-Research-midi2-layer-50-train3000](https://clyp.it/xto2didu)

[Rocksetta-Magenta-Research-midi2-layer500-train300](https://clyp.it/klpanuli)



.


.



.








#June 27, 2016

When everything is done every training run should end up zipped in the named folders so that you can setup my training run with your own primer.mid file. Those folders should also include the .mid file output as well as a converted output to .mp3



The All-inputs folder has the 2 midi file inputs (a-few-of-my-favorite-things.mid and god-rest-ye-merry-gentlemen.mid) and fur-elise.mid as the primer.mid file

Please make Pull Requests with the same folder labelling scheme

midi2.LAYERS.TRAINING

Obviously we are going to do runs with more than two midi files but I needed to make things simple here to look for patterns.

# Use at your own risk

By Jeremy Ellis

Maker of http://www.rocksetta.com

Twitter @rocksetta
