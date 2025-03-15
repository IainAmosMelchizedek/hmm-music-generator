# hmm-music-generator
A simple project using a Hidden Markov Model (HMM) to generate musical notes, visualize melodies, and save them as MIDI files.

HMM Music GeneratorOverviewThis project demonstrates how a Hidden Markov Model (HMM) can be used to generate musical sequences. It creates a melody by defining musical moods (calm, energetic, melancholic), generates note sequences, plots them on a music staff, and saves them as a MIDI file for playback.
FeaturesGenerates melodies based on probabilistic models.
Plots the generated music sequence on a music staff.
Saves the melody as a MIDI file to be played in DAWs or MIDI players.

1. Installation1. Clone the Repository:

git clone https://github.com/IainAmosMelchizedek/hmm-music-generator.git
cd hmm-music-generator

2. Set Up a Virtual Environment (Optional)

conda create -n hmm-music python=3.7.6 pip
conda activate hmm-music

3.  Install Required Packages:

pip install pomegranate numpy scipy matplotlib midiutil

Usage:
Run the Python script to generate and visualize a melody:
After running, a MIDI file (generated_melody.mid) will be saved. You can open this in MuseHub, FL Studio, Ableton, or any MIDI player.

Example Output: 
Generated melody: ['C' 'E' 'G' 'F' 'F' 'C' 'F' 'F' 'F' 'F']
MIDI file 'generated_melody.mid' saved successfully!

LicenseThis project is licensed under the MIT License - see the LICENSE file for details.

ContributingFeel free to submit pull requests or open an issue if you have improvements or questions.
