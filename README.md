# Modified source files for addding [MTS-ESP](https://github.com/ODDSound/MTS-ESP) support to [Cardinal](https://github.com/DISTRHO/Cardinal)

HostMIDI.cpp is a modified version of plugins/Cardinal/src/HostMIDI.cpp with some code added from [MTS-ESP-VCVRack](https://github.com/ODDSound/MTS-ESP-VCVRack), (specifically from MIDI_CV_MTS_ESP.cpp). In addition to these changes, the MTS Client files libMTSClient.h and libMTSClient.cpp from [MTS-ESP](https://github.com/ODDSound/MTS-ESP) must be added to plugins/Cardinal/src/ when building Cardinal.

# Credits and attribution
[Cardinal](https://github.com/DISTRHO/Cardinal): [GNU General Public License v3.0](https://github.com/DISTRHO/Cardinal/blob/main/LICENSE)

[MTS-ESP](https://github.com/ODDSound/MTS-ESP): [BSD Zero Clause License](https://github.com/ODDSound/MTS-ESP/blob/main/LICENSE) Copyright (C) 2021 by ODDSound Ltd. info@oddsound.com

[MTS-ESP-VCVRack](https://github.com/ODDSound/MTS-ESP-VCVRack): [BSD Zero Clause License](https://github.com/ODDSound/MTS-ESP-VCVRack/blob/main/LICENSE) Copyright (C) 2021 by ODDSound Ltd. info@oddsound.com
