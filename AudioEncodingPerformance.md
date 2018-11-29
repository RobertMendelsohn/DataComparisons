# Size Comparison of Various Audio Encoding Schemes

What audio encoding scheme produces the smallest files for short (<30 second) English audio? 100 16kHz 16-bit samples were downloaded from [VoxForge](http://www.voxforge.org/) from this [page](http://www.repository.voxforge1.org/downloads/SpeechCorpus/Trunk/Audio/Main/16kHz_16bit/). The files were then imported in Mathematica and exported in various formats and their file sizes recorded.

### Data Properties

| Property | Value |
| --- | --- |
| # of Files | 100 files |
| Median File Size | 148 kB |
| Median File Length | 4.62 s |

### Results

| Encoding | Min. Length (kB) | Median Length (kB) | Mean Length (kB) | Max. Length (kB) |
| --- | --- | --- | --- | --- |
| OGG | 17 | 28 | 30 | 76 | 
| MP3 | 21 | 35 | 39 | 103 | 
| M4A | 79 | 79 | 79 | 79 | 
| FLAC | 41 | 87 | 95 | 265 | 
| AU | 88 | 148 | 164 | 448 | 
| SND | 88 | 148 | 164 | 448 | 
| WAV | 88 | 148 | 164 | 448 | 
| AIFF | 88 | 148 | 164 | 448 | 
| WAVE64 | 88 | 148 | 164 | 448 | 
