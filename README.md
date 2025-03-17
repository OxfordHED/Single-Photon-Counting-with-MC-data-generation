# SPC_MC
Single Photon Counting and Artificial Data



Copy right SHI, YuanFeng  石元峰 
@ 2022 Jan 09



To generate new data, please use "MC_new.py" -> this creates an npy file under data_set_xxx.npy

Then run the cluster algorithm through "FAST-SPC.py" -> this records the energy of each photons "xxx_photons.json"

Run "gen-hist.py" -> this generates the histogram of the photons "xxx_hists.npy"

Run "deconvolution.py" to show the final result once an appropriate deconvolution strength is set up (usually 2 x fill fraction) -> ""


