# whisperzh
🔥 📗 [Whisper](https://github.com/openai/whisper) transcripts of Andrej Karpathy's [Neural Networks: Zero to Hero course lectures](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ). 💎 💥

<img src="buffdogedrej.png?raw=true" width="600"/>

## Transcripts

| Project | Files | Lecture 
|-|-|-|
|micrograd| [txt](micrograd/micrograd.txt?raw=true)/[json](micrograd/micrograd.json?raw=true)/[srt](micrograd/micrograd.srt?raw=true)/[tsv](micrograd/micrograd.tsv?raw=true)/[vtt](micrograd/micrograd.vtt?raw=true)/[stdout](micrograd/output.txt?raw=true) |[The spelled-out intro to neural networks and backpropagation: building micrograd](https://www.youtube.com/watch?v=VMj-3S1tku0)|
|makemore1| [txt](makemore1/makemore1.txt?raw=true)/[json](makemore1/makemore1.json?raw=true)/[srt](makemore1/makemore1.srt?raw=true)/[tsv](makemore1/makemore1.tsv?raw=true)/[vtt](makemore1/makemore1.vtt?raw=true)/[stdout](makemore1/output.txt?raw=true) |[The spelled-out intro to language modeling: building makemore](https://www.youtube.com/watch?v=PaCmpygFfXo)|
|makemore2| [txt](makemore2/makemore2.txt?raw=true)/[json](makemore2/makemore2.json?raw=true)/[srt](makemore2/makemore2.srt?raw=true)/[tsv](makemore2/makemore2.tsv?raw=true)/[vtt](makemore2/makemore2.vtt?raw=true)/[stdout](makemore2/output.txt?raw=true) |[Building makemore Part 2: MLP](https://www.youtube.com/watch?v=TCH_1BHY58I)|
|makemore3| [txt](makemore3/makemore3.txt?raw=true)/[json](makemore3/makemore3.json?raw=true)/[srt](makemore3/makemore3.srt?raw=true)/[tsv](makemore3/makemore3.tsv?raw=true)/[vtt](makemore3/makemore3.vtt?raw=true)/[stdout](makemore3/output.txt?raw=true) |[Building makemore Part 3: Activations & Gradients, BatchNorm](https://www.youtube.com/watch?v=P6sfmUTpUmc)|
|makemore4| [txt](makemore4/makemore4.txt?raw=true)/[json](makemore4/makemore4.json?raw=true)/[srt](makemore4/makemore4.srt?raw=true)/[tsv](makemore4/makemore4.tsv?raw=true)/[vtt](makemore4/makemore4.vtt?raw=true)/[stdout](makemore4/output.txt?raw=true) |[Building makemore Part 4: Becoming a Backprop Ninja](https://www.youtube.com/watch?v=q8SA3rM6ckI)|
|makemore5| [txt](makemore5/makemore5.txt?raw=true)/[json](makemore5/makemore5.json?raw=true)/[srt](makemore5/makemore5.srt?raw=true)/[tsv](makemore5/makemore5.tsv?raw=true)/[vtt](makemore5/makemore5.vtt?raw=true)/[stdout](makemore5/output.txt?raw=true) |[Building makemore Part 5: Building a WaveNet](https://www.youtube.com/watch?v=t3YJ5hKiMQ0)|
|nanoGPT| [txt](nanoGPT/nanoGPT.txt?raw=true)/[json](nanoGPT/nanoGPT.json?raw=true)/[srt](nanoGPT/nanoGPT.srt?raw=true)/[tsv](nanoGPT/nanoGPT.tsv?raw=true)/[vtt](nanoGPT/nanoGPT.vtt?raw=true)/[stdout](nanoGPT/output.txt?raw=true)|[Let's build GPT: from scratch, in code, spelled out.](https://www.youtube.com/watch?v=kCc8FmEb1nY) |
|stateofGPT| [txt](stateofGPT/stateofGPT.txt?raw=true)/[json](stateofGPT/stateofGPT.json?raw=true)/[srt](stateofGPT/stateofGPT.srt?raw=true)/[tsv](stateofGPT/stateofGPT.tsv?raw=true)/[vtt](stateofGPT/stateofGPT.vtt?raw=true)/[stdout](stateofGPT/output.txt?raw=true) |[State of GPT](https://www.youtube.com/watch?v=bZQun8Y4L2A) |
|minbpe| [txt](minbpe/minbpe.txt?raw=true)/[json](minbpe/minbpe.json?raw=true)/[srt](minbpe/minbpe.srt?raw=true)/[tsv](minbpe/minbpe.tsv?raw=true)/[vtt](minbpe/minbpe.vtt?raw=true)/[stdout](minbpe/output.txt?raw=true) |[Let's build the GPT Tokenizer](https://www.youtube.com/watch?v=zduSFxRajkE)|

## Commands
1. [yt-dlp](https://github.com/yt-dlp/yt-dlp) to download lectures:
```bash
yt-dlp --yes-playlist --x --audio-format mp3 {playlist_link}`
```
2. [openai/whisper](https://github.com/openai/whisper) to transcribe them:
```bash
whisper --language en --model large -o {out_dir} -- {mp3_file}
```

## Acknowledgements
- [@karpathy](https://github.com/karpathy)'s [nn-zero-to-hero](https://github.com/karpathy/nn-zero-to-hero)
- [@averkij](https://github.com/averkij)'s [karcaps](https://github.com/averkij/karcaps)
