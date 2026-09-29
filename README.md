# Awesome AI Video APIs [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI video, audio and image generation APIs developers can call, plus open models and tooling.

Every entry links to the provider's official pricing or API docs page. Prices change often, so check the linked page before you build on one.

## Contents

- [Text to Video](#text-to-video)
- [Image to Video](#image-to-video)
- [Video Editing and Rendering](#video-editing-and-rendering)
- [Avatars and Lipsync](#avatars-and-lipsync)
- [Text to Speech and Voice](#text-to-speech-and-voice)
- [Music and Sound](#music-and-sound)
- [Image Generation](#image-generation)
- [API Aggregators](#api-aggregators)
- [Open Models](#open-models)
- [SDKs and Tools](#sdks-and-tools)
- [Guides](#guides)

## Text to Video

- [Google Veo](https://ai.google.dev/gemini-api/docs/pricing) - Veo video models with native audio, called through the Gemini API. Price: Veo 3.1 Standard at $0.40 per second for 720p and 1080p, Fast at $0.10 per second for 720p.
- [Kling AI](https://app.klingai.com/global/dev/document-api/apiReference/commonInfo) - Developer API for the Kling video models, with text to video and camera control.
- [Luma Dream Machine](https://docs.lumalabs.ai/docs/api) - API for the Ray video models, including keyframes and extensions.
- [Magic Hour](https://docs.magichour.ai/billing/overview) - Video generation API covering text to video, image to video and face swap. Price: Creator plan $19 per month with 12,000 credits, or credit packs from $10 for 4,000 credits.
- [MiniMax Hailuo](https://platform.minimax.io/docs/pricing/overview) - Hailuo video models plus text, speech and music endpoints under one platform.
- [OpenAI Sora](https://developers.openai.com/api/docs/pricing) - Sora video generation in the OpenAI API. Price: $0.10 per second at 720p, and $0.50 per second at 1024p on the pro model.
- [Runway](https://docs.dev.runwayml.com/guides/pricing/) - Developer API for the Gen-4 and Aleph video models. Price: credits cost $0.01 each and Gen-4 Turbo uses 5 credits per second.
- [Vidu](https://platform.vidu.com/docs) - API for the Vidu video models, including reference to video with consistent subjects.

## Image to Video

- [Hedra](https://www.hedra.com/pricing) - Character video generation that animates a still image with speech. Price: Basic plan $15 per month with 1,500 credits.
- [Kling AI image to video](https://app.klingai.com/global/dev/document-api/apiReference/model/imageToVideo) - Endpoint that animates a start frame, with an optional end frame.
- [PixVerse](https://docs.pixverse.ai/) - Image to video and effect templates through a REST API.
- [Runway API](https://docs.dev.runwayml.com/guides/using-the-api/) - Image to video generation with the Gen-4 models, driven by a start frame and a prompt.
- [Stability AI video](https://platform.stability.ai/docs/api-reference) - Image to video endpoint built on Stable Video Diffusion.

## Video Editing and Rendering

- [api.video](https://api.video/pricing/) - Video upload, transcoding, hosting and playback API. Price: hosting from $0.00285 per minute of video stored and delivery from $0.0017 per minute delivered, with free encoding.
- [Bannerbear](https://www.bannerbear.com/pricing/) - Generates images and short videos from templates over an API. Price: Automate plan $49 per month with 1,000 API credits.
- [Cloudinary](https://cloudinary.com/pricing) - Media storage, transformation and delivery API for images and video. Price: free plan with 25 monthly credits, Plus at $99 per month with 225 credits.
- [Creatomate](https://creatomate.com/pricing) - Template-based video and image generation API for automation workflows.
- [JSON2Video](https://json2video.com/pricing/) - Renders video from a JSON description of scenes, text and media. Price: Hobby plan $16.95 per month for up to 50 minutes of rendered output.
- [Mux](https://www.mux.com/pricing) - Video infrastructure API for on-demand and live streaming with analytics. Price: on-demand storage $0.00300 per minute per month and delivery $0.00100 per minute after 100,000 free minutes per month.
- [Plainly](https://www.plainly.com/pricing) - Renders After Effects templates at scale through an API.
- [Rendi](https://rendi.dev/pricing) - Runs FFmpeg commands as a hosted API so you do not manage servers. Price: Pro plans from $25 per month, as low as $0.10 per GB processed.
- [Shotstack](https://shotstack.io/pricing/) - Cloud video editing API driven by a JSON timeline. Price: $0.30 per minute pay as you go, or $0.20 per minute on a subscription from $39 per month.
- [Topaz Labs](https://www.topazlabs.com/api) - Upscaling and enhancement API for images and video. Price: Developer plan $50 per month with 500 credits, at $0.10 per credit.
- [Transloadit](https://transloadit.com/pricing/) - File processing API with encoding, resizing and watermarking robots. Price: Lite plan $29 per month including 15 GB, overage at $2 per GB.

## Avatars and Lipsync

- [Akool](https://www.akool.com/pricing) - API for talking avatars, face swap and video translation.
- [Creatify](https://www.creatify.ai/pricing) - Generates avatar ad videos from a product URL or script. Price: Starter plan $39 per month with 100 credits.
- [D-ID](https://docs.d-id.com/reference/get-started) - Talking head videos and real-time agents from a photo and a voice.
- [HeyGen](https://www.heygen.com/pricing) - Avatar video generation, voice cloning and translation over an API. Price: Creator plan $29 per month with 600 credits.
- [Sync](https://sync.so/pricing) - Lipsync API that matches mouth movement in a video to new audio. Price: Hobbyist plan $5 per month plus $0.05 per second of generated video.
- [Synthesia](https://www.synthesia.io/pricing) - Studio avatar video platform with an API for scripted videos. Price: API access starts on the Creator plan at $89 per month, which includes 360 minutes of API video per year.
- [Tavus](https://www.tavus.io/pricing) - Real-time conversational video agents and personalized video replicas. Price: Starter plan $59 per month, extra conversational minutes at $0.37.

## Text to Speech and Voice

- [Amazon Polly](https://aws.amazon.com/polly/pricing/) - AWS speech synthesis with standard, neural, long-form and generative voices. Price: $4.00 per 1M characters for Standard, $16.00 for Neural, $30 for Generative and $100 for Long-Form.
- [Azure AI Speech](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/speech-services/) - Microsoft neural text to speech, transcription and voice conversion.
- [Cartesia](https://cartesia.ai/pricing) - Low-latency speech synthesis and voice cloning for agents. Price: free plan with 20,000 credits per month, Pro at $5 per month with 100,000 credits.
- [Deepgram](https://deepgram.com/pricing) - Aura speech synthesis alongside Nova transcription. Price: Aura-2 at $0.030 per 1,000 characters, Nova-3 transcription from $0.0048 per minute.
- [ElevenLabs](https://elevenlabs.io/pricing) - Speech synthesis, voice cloning, dubbing and speech to text. Price: free plan with 10,000 credits per month, Starter at $6 per month with 30,000 credits.
- [Fish Audio](https://docs.fish.audio/) - Open-weight speech models served through a hosted API with voice cloning.
- [Google Cloud Text-to-Speech](https://cloud.google.com/text-to-speech/pricing) - Speech synthesis with Standard, WaveNet, Neural2 and Chirp voices.
- [Hume](https://www.hume.ai/pricing) - Octave speech synthesis with emotional control and voice design. Price: $0.15 per 1,000 characters on the free plan, down to $0.05 per 1,000 on Pro.
- [Murf](https://murf.ai/api/pricing) - Speech synthesis, dubbing and voice changer endpoints.
- [OpenAI audio](https://platform.openai.com/docs/guides/text-to-speech) - Speech synthesis models in the OpenAI API, with instructions for steering delivery.
- [Resemble AI](https://www.resemble.ai/pricing/) - Voice cloning, speech synthesis and deepfake detection API.
- [Rime](https://rime.ai/pricing) - Conversational speech models built for phone and support agents. Price: $0.03 per 1,000 characters on Mist v3 and $0.05 per 1,000 on Coda.

## Music and Sound

- [AudioShake](https://www.audioshake.ai/) - Stem separation API that splits a mix into vocals, drums and other parts.
- [Beatoven.ai](https://beatoven.ai/api) - Generates royalty-free background music from a mood and duration.
- [ElevenLabs Music](https://elevenlabs.io/docs/api-reference/introduction) - Music and sound effect generation next to the voice endpoints.
- [Lalal.ai](https://www.lalal.ai/api/) - Stem splitting and voice cleaning API for audio and video files.
- [Loudly](https://www.loudly.com/music-api) - Music generation API with volume-based licensing for apps.
- [Mubert](https://mubert.com/render/pricing) - Generative music streams and tracks for apps and video. Price: Creator plan $14 per month, Pro at $39 per month.
- [Soundraw](https://soundraw.io/api) - Music generation API with per-section editing and commercial licensing.
- [Stable Audio](https://stability.ai/stable-audio) - Text to audio generation for music and sound effects from Stability AI.

## Image Generation

- [Black Forest Labs](https://docs.bfl.ai/) - FLUX image generation, editing and in-painting endpoints.
- [Bria](https://bria.ai/pricing) - Image generation and editing trained on licensed data, with attribution.
- [Clipdrop](https://clipdrop.co/apis/pricing) - Background removal, cleanup, relighting and upscaling endpoints.
- [Freepik](https://docs.freepik.com/introduction) - One API routing to several image and video generation models.
- [Getimg.ai](https://getimg.ai/pricing) - Image generation, editing and upscaling across many open models.
- [Google Gemini images](https://ai.google.dev/gemini-api/docs/image-generation) - Native image generation and conversational editing in the Gemini API.
- [Ideogram](https://developer.ideogram.ai/) - Image generation with strong text rendering, plus editing and upscaling.
- [Leonardo.Ai](https://docs.leonardo.ai/docs/getting-started) - Image generation API with fine-tuned models and element styles.
- [OpenAI images](https://developers.openai.com/api/docs/guides/image-generation) - Image generation and editing with the gpt-image models.
- [Photoroom](https://www.photoroom.com/api/pricing) - Background removal and product photo editing API.
- [Recraft](https://www.recraft.ai/pricing) - Image and vector generation with brand style controls.
- [remove.bg](https://www.remove.bg/api) - Background removal API for people, products and cars.
- [Stability AI](https://platform.stability.ai/pricing) - Stable Diffusion image generation, editing, control and upscaling.-
- [VELIN Image API](https://72agi.com/nano-banana-api-pricing.html) - Pay-per-image async REST API for Nano Banana Pro/2 and GPT Image 2/2.5, up to 14 reference images, failed generations not charged. Price: about $0.037 per image, flat at 1K/2K/4K.

## API Aggregators

- [AI/ML API](https://aimlapi.com/ai-ml-api-pricing) - One key for hundreds of text, image, video and audio models.
- [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/platform/pricing/) - Serverless inference for open image, speech and text models on Cloudflare's network.
- [DeepInfra](https://deepinfra.com/pricing) - Hosted open models for text, image and audio with per-token billing.
- [Eden AI](https://www.edenai.co/pricing) - Single API that normalizes many vendors for speech, image and video tasks.
- [fal.ai](https://fal.ai/pricing) - Generative media platform with fast image, video and audio model endpoints. Price: video billed per second or per video, for example Kling 2.5 Turbo Pro at $0.07 per second, and images from $0.02 per megapixel.
- [Fireworks AI](https://fireworks.ai/pricing) - Serverless and dedicated inference for open text, image and audio models.
- [Hugging Face Inference Providers](https://huggingface.co/docs/inference-providers/pricing) - One API routing text to video, image and speech requests to partner providers.
- [Novita AI](https://novita.ai/pricing) - Hosted open models for image, video and speech plus GPU instances.
- [Replicate](https://replicate.com/pricing) - Runs thousands of community models behind a single API. Price: billed per second of compute, for example Nvidia L40S at $0.000975 per second, with some models billed per output.
- [Runware](https://runware.ai/pricing) - Single API for image, video and audio generation on its own inference stack.
- [Segmind](https://www.segmind.com/pricing) - Serverless endpoints and pipelines for image and video models.
- [SiliconFlow](https://www.siliconflow.com/pricing) - Pay-as-you-go API for open text, image, video and audio models.
- [Together AI](https://www.together.ai/pricing) - Inference and fine-tuning for open models, including image generation.

## Open Models

- [ACE-Step](https://github.com/ace-step/ACE-Step) - Music generation model that writes full songs with vocals. License: Apache-2.0.
- [AnimateDiff](https://github.com/guoyww/AnimateDiff) - Adds motion to existing Stable Diffusion checkpoints without retraining. License: Apache-2.0.
- [AudioCraft](https://github.com/facebookresearch/audiocraft) - Research codebase for MusicGen and AudioGen generation models. License: MIT.
- [Chatterbox](https://github.com/resemble-ai/chatterbox) - Speech synthesis model with zero-shot voice cloning and emotion control. License: MIT.
- [CogVideo](https://github.com/THUDM/CogVideo) - Text to video and image to video model family from Tsinghua. License: Apache-2.0.
- [Coqui TTS](https://github.com/coqui-ai/TTS) - Toolkit with many speech synthesis and voice cloning models. License: MPL-2.0.
- [F5-TTS](https://github.com/SWivid/F5-TTS) - Flow matching speech synthesis with fast zero-shot cloning. License: MIT.
- [FLUX.1 dev](https://huggingface.co/black-forest-labs/FLUX.1-dev) - Guidance-distilled image generation model from Black Forest Labs. License: FLUX.1 dev non-commercial license.
- [FramePack](https://github.com/lllyasviel/FramePack) - Next frame prediction that makes long video generation fit in low VRAM. License: Apache-2.0.
- [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo) - Large video generation model from Tencent with open weights. License: Tencent Hunyuan Community License.
- [Kokoro-82M](https://huggingface.co/hexgrad/Kokoro-82M) - Small speech synthesis model that runs fast on modest hardware. License: Apache-2.0.
- [LatentSync](https://github.com/bytedance/LatentSync) - Lipsync model that edits mouth movement in latent space. License: Apache-2.0.
- [LTX-Video](https://github.com/Lightricks/LTX-Video) - Real-time video generation model from Lightricks. License: Apache-2.0.
- [Mochi](https://github.com/genmoai/mochi) - Video generation model from Genmo with open weights. License: Apache-2.0.
- [Open-Sora](https://github.com/hpcaitech/Open-Sora) - Open reproduction of a Sora-style video generation pipeline. License: Apache-2.0.
- [Qwen-Image](https://github.com/QwenLM/Qwen-Image) - Image generation and editing model with strong text rendering. License: Apache-2.0.
- [SadTalker](https://github.com/OpenTalker/SadTalker) - Generates a talking head video from one photo and an audio clip. License: Apache-2.0.
- [Stable Audio Open](https://huggingface.co/stabilityai/stable-audio-open-1.0) - Open weights for generating short audio samples and sound effects. License: Stability AI Community License.
- [Stable Diffusion 3.5 Large](https://huggingface.co/stabilityai/stable-diffusion-3.5-large) - Image generation model from Stability AI with open weights. License: Stability Community License.
- [Stable Video Diffusion](https://huggingface.co/stabilityai/stable-video-diffusion-img2vid-xt) - Image to video model that produces short clips from a still frame. License: Stable Video Diffusion Community License.
- [Wan 2.2](https://github.com/Wan-Video/Wan2.2) - Video generation model family from Alibaba covering text and image inputs. License: Apache-2.0.
- [Wav2Lip](https://github.com/Rudrabha/Wav2Lip) - Classic lipsync model that matches mouth movement to any speech. License: non-commercial research use only.
- [Whisper](https://github.com/openai/whisper) - Speech recognition and translation model from OpenAI. License: MIT.

## SDKs and Tools

- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) - Node graph interface and backend for running image and video models. License: GPL-3.0.
- [Diffusers](https://huggingface.co/docs/diffusers/index) - Python library for running and training diffusion models. License: Apache-2.0.
- [FFmpeg](https://ffmpeg.org/documentation.html) - The standard command line tool for decoding, encoding and filtering video.
- [LiveKit Agents](https://docs.livekit.io/agents) - Framework for realtime voice and video agents on WebRTC. License: Apache-2.0.
- [MoviePy](https://zulko.github.io/moviepy) - Python library for cutting, compositing and rendering video. License: MIT.
- [Pipecat](https://docs.pipecat.ai) - Python framework for realtime voice and multimodal pipelines. License: BSD-2-Clause.
- [Remotion](https://remotion.dev/license) - Renders video from React components, with a paid license for companies.
- [Revideo](https://re.video) - TypeScript library for programmatic video built on Motion Canvas. License: MIT.

## Guides

- [ComfyUI documentation](https://docs.comfy.org) - Official guide to nodes, workflows and the ComfyUI API.
- [ElevenLabs quickstart](https://elevenlabs.io/docs/quickstart) - First speech synthesis call in a few minutes.
- [fal.ai documentation](https://docs.fal.ai) - Queue, streaming and webhook patterns for generative media jobs.
- [Gemini API video generation](https://ai.google.dev/gemini-api/docs/video) - How to call Veo and handle the long-running operation.
- [Hugging Face text to video](https://huggingface.co/tasks/text-to-video) - Task page explaining the models, datasets and metrics.
- [OpenAI video generation](https://platform.openai.com/docs/guides/video-generation) - Guide to creating, polling and downloading Sora videos.
- [Replicate documentation](https://replicate.com/docs) - How to run models, stream output and push your own.
- [Runway API documentation](https://docs.dev.runwayml.com) - Endpoints, task polling and model options for the developer API.

## Related Lists

- [alihesari/awesome-free-ai-apis](https://github.com/alihesari/awesome-free-ai-apis) - AI APIs with free tiers, free credits and free models.
- [krzemienski/awesome-video](https://github.com/krzemienski/awesome-video) - Video encoding, streaming and player resources.
- [public-apis/public-apis](https://github.com/public-apis/public-apis) - Free public APIs across every category.
- [steven2358/awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai) - Generative AI tools, models and services.

## Contributing

Contributions are welcome. Read the [contribution guidelines](CONTRIBUTING.md) first.

---

Maintained by [Ali Hesari](https://alihesari.com). Follow on [GitHub](https://github.com/alihesari) and [X](https://x.com/alihesari) for updates.
