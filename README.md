# Vector-Music (Text-to-Music Generator 🎵)

A Streamlit web app that generates music from a text prompt using Meta’s **AudioCraft MusicGen (musicgen-small)** model.  
Enter a description (e.g., “lofi chill beats with soft piano”) and choose a duration — the app generates an audio clip you can preview and download.

---

## Demo (What it does)

- Takes a **text description** as input
- Lets you select **duration (seconds)**
- Generates music using **MusicGen Small**
- Saves output as a `.wav` file in `audio_output/`
- Plays audio in the browser and provides a **download link**

---

## Tech Stack

- **Python**
- **Streamlit** (UI)
- **AudioCraft / MusicGen** (model)
- **PyTorch + TorchAudio** (tensor + audio saving)

---


---

Setup & Installation

1) Clone the repository
git clone https://github.com/rishabshukla-code/Vector-Music.git
cd Vector-Music


2) Create and activate a virtual environment (recommended)
Windows (Git Bash):

python -m venv venv
source venv/Scripts/activate

3) Install dependencies
pip install -r requirements.txt

4) Run the App
streamlit run app.py
