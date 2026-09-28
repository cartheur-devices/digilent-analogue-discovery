## The Digilent Analog Discovery 2

A small device that leverages (still) powerful features.

![image](/images/analog_discovery_2.png)

### Installation onto Linux

In the `lib` folder, do the following:

```
sudo dkpg -i digilent.adept.runtime_2.30.1_amd64.deb
sudo dpkg -i digilent.waveforms_3.25.1_amd64.deb
```

If you are having issues around dependencies, run:

`sudo dpkg-deb --info digilent.waveforms_3.25.1_amd64.deb`
