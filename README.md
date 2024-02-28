# whisperzh
[Whisper](https://github.com/openai/whisper) transcripts of Andrej Karpathy's [Neural Networks: Zero to Hero course lectures](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ).

| Acronym | Transcripts | Lecture 
| - | - | - |
|`micrograd`|txt/json/srt/tsv/vtt/cmdoutput|[`The spelled-out intro to neural networks and backpropagation: building micrograd`](https://www.youtube.com/watch?v=VMj-3S1tku0)|
|`makemore1`|txt/json/srt/tsv/vtt/cmdoutput|[`The spelled-out intro to language modeling: building makemore`](https://www.youtube.com/watch?v=PaCmpygFfXo)|
|`makemore2`|txt/json/srt/tsv/vtt/cmdoutput|[`Building makemore Part 2: MLP`](https://www.youtube.com/watch?v=TCH_1BHY58I)|
|`makemore3`|txt/json/srt/tsv/vtt/cmdoutput|[`Building makemore Part 3: Activations & Gradients, BatchNorm`](https://www.youtube.com/watch?v=P6sfmUTpUmc)|
|`makemore4`|txt/json/srt/tsv/vtt/cmdoutput|[`Building makemore Part 4: Becoming a Backprop Ninja`](https://www.youtube.com/watch?v=q8SA3rM6ckI)|
|`makemore5`|txt/json/srt/tsv/vtt/cmdoutput|[`Building makemore Part 5: Building a WaveNet`](https://www.youtube.com/watch?v=t3YJ5hKiMQ0)|
|`nanoGPT`|txt/json/srt/tsv/vtt/cmdoutput|[`Let's build GPT: from scratch, in code, spelled out.`](https://www.youtube.com/watch?v=kCc8FmEb1nY)|
|`stateofGPT`|txt/json/srt/tsv/vtt/cmdoutput|[`State of GPT`](https://www.youtube.com/watch?v=bZQun8Y4L2A) |
|`minbpe`|txt/json/srt/tsv/vtt/cmdoutput|[`Let's build the GPT Tokenizer`](https://www.youtube.com/watch?v=zduSFxRajkE)|

## Tools
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
