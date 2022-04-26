# rtmonoaudio2midi
Real-time note recognition in monophonic audio stream

Please install all the dependencies from `requirements.txt` file by executing:
`pip install -r requirements.txt`

To run the app:
* Download a SoundFont file and update a path to it in the `app_setup.py` file
* Execute ` python audiostream.py`

Troubleshooting
I get an error about fluidsynth :
   ImportError: Couldn't find the FluidSynth library
   https://github.com/FluidSynth/fluidsynth/issues/657

Check python version: get 3.7
get pyaudio https://stackoverflow.com/questions/54998028/how-do-i-install-pyaudio-on-python-3-7
get .dll https://github.com/FluidSynth/fluidsynth/wiki/BuildingWithCMake#building-with-msys2-on-windows