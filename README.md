# Awesome AI Micro Drama [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Open-source tools for making AI micro dramas (vertical, serialized short dramas), sorted by what they do. Every entry has a plain-English write-up, quickstart and daily GitHub stats on **[OpenMicroDrama](https://openmicrodrama.com)**.

Many of the best projects have Chinese-only READMEs. The one-line descriptions here are ours. Licenses vary a lot: anything marked ⚠️ is non-commercial, source-available or custom, so read its license before you build on it.

## Contents

- [All-in-one platforms](#all-in-one-platforms)
- [Agent skill collections](#agent-skill-collections)
- [Script and story](#script-and-story)
- [Storyboards and consistency](#storyboards-and-consistency)
- [Prompt collections](#prompt-collections)
- [ComfyUI workflows](#comfyui-workflows)
- [Editing, voice and audio](#editing-voice-and-audio)
- [Video agents and frameworks](#video-agents-and-frameworks)
- [Model tooling](#model-tooling)
- [Datasets and papers](#datasets-and-papers)
- [Individual agent skills](#individual-agent-skills)
- [Guides and prompts](#guides-and-prompts)
- [Contributing](#contributing)

## All-in-one platforms

Apps you run yourself that take a script or a novel to finished episodes.

- [Toonflow-app](https://github.com/HBAI-Ltd/Toonflow-app) ★16k - One infinite canvas for AI short dramas and comic dramas. ([write-up](https://openmicrodrama.com/projects/hbai-ltd-toonflow-app))
- [huobao-drama](https://github.com/chatfire-AI/huobao-drama) ★16k - Novel in, finished short-drama episode out, with script and storyboard. ⚠️ CC-BY-NC-SA-4.0 ([write-up](https://openmicrodrama.com/projects/chatfire-ai-huobao-drama))
- [waoowaoo](https://github.com/waooAI/waoowaoo) ★14k - Self-hosted AI workspace for making images and short-drama video. ⚠️ Elastic-2.0 ([write-up](https://openmicrodrama.com/projects/waooai-waoowaoo))
- [dramaclaw](https://github.com/dramaclaw/dramaclaw) ★6.6k - Feed it a manuscript, get planned episodes and a cut film. ⚠️ Elastic-2.0 ([write-up](https://openmicrodrama.com/projects/dramaclaw-dramaclaw))
- [Jellyfish](https://github.com/Forget-C/Jellyfish) ★6.6k - Storyboards and linked assets from chapter scripts. ([write-up](https://openmicrodrama.com/projects/forget-c-jellyfish))
- [ArcReel](https://github.com/ArcReel/ArcReel) ★5.3k - Builds AI comic dramas and short videos from novels or scripts. ([write-up](https://openmicrodrama.com/projects/arcreel-arcreel))
- [moyin-creator](https://github.com/MemeCalculate/moyin-creator) ★4.6k - Desktop app that turns scripts into storyboards and AI clips. ([write-up](https://openmicrodrama.com/projects/memecalculate-moyin-creator))
- [printfilm](https://github.com/yi1108/printfilm) ★4.1k - Give it a topic or script, get storyboards and video. ([write-up](https://openmicrodrama.com/projects/yi1108-printfilm))
- [LocalMiniDrama](https://github.com/xuanyustudio/LocalMiniDrama) ★1.9k - Free desktop app for AI short dramas and comic dramas on your computer. ([write-up](https://openmicrodrama.com/projects/xuanyustudio-localminidrama))
- [AIComicBuilder](https://github.com/LingyiChen-AI/AIComicBuilder) ★1.9k - Writes an animated comic drama from your script, shot by shot. ([write-up](https://openmicrodrama.com/projects/lingyichen-ai-aicomicbuilder))
- [VideoClaw](https://github.com/HITsz-TMG/VideoClaw) ★1.8k - AI director that turns one idea into a full short drama or comic drama. ([write-up](https://openmicrodrama.com/projects/hitsz-tmg-videoclaw))
- [ai_story](https://github.com/xhongc/ai_story) ★1.7k - Paste a story topic, get script, storyboard, images and clips. ⚠️ CC-BY-NC-SA-4.0 ([write-up](https://openmicrodrama.com/projects/xhongc-ai-story))
- [ai-moive-studio](https://github.com/869413421/ai-moive-studio) ★1.6k - Self-hosted infinite canvas for AI video, with a workflow assistant. ([write-up](https://openmicrodrama.com/projects/869413421-ai-moive-studio))
- [ai-fusion-video](https://github.com/Stonewuu/ai-fusion-video) ★1.6k - Keeps scripts, storyboards, assets and clips in one self-hosted workspace. ([write-up](https://openmicrodrama.com/projects/stonewuu-ai-fusion-video))
- [LingGuo-Drama](https://github.com/LingGuoAI/LingGuo-Drama) ★1.5k - Self-hosted workbench that turns a script into a mini-drama or motion comic. ([write-up](https://openmicrodrama.com/projects/lingguoai-lingguo-drama))
- [lumenx](https://github.com/alibaba/lumenx) ★1.3k - Feed it novel text, get a motion-comic short drama with dialogue. ([write-up](https://openmicrodrama.com/projects/alibaba-lumenx))
- [infinite-canvas](https://github.com/tigerowo/infinite-canvas) ★1.1k - Open-source canvas for AI image, video and audio creation. ([write-up](https://openmicrodrama.com/projects/tigerowo-infinite-canvas))
- [open-ai-canvas](https://github.com/ddcat-ai/open-ai-canvas) ★1.1k - Plans AI short dramas on a free-form canvas. ([write-up](https://openmicrodrama.com/projects/ddcat-ai-open-ai-canvas))
- [aid-studio](https://github.com/gzxx-2025/aid-studio) ★698 - Self-hosted studio for AI motion comics and short dramas, script to video. ([write-up](https://openmicrodrama.com/projects/gzxx-2025-aid-studio))
- [TapCanvas](https://github.com/anymouschina/TapCanvas) ★639 - Puts scripts, characters, storyboards and video on one infinite canvas. ([write-up](https://openmicrodrama.com/projects/anymouschina-tapcanvas))
- [Nomi](https://github.com/aqm857886159/Nomi) ★537 - Edit shots and timelines in a local AI video studio. ([write-up](https://openmicrodrama.com/projects/aqm857886159-nomi))
- [CineGen-ShortDrama](https://github.com/UllrAI/CineGen-ShortDrama) ★536 - Keyframes and Veo clips from a script in your browser. ⚠️ NOASSERTION ([write-up](https://openmicrodrama.com/projects/ullrai-cinegen-shortdrama))
- [Open-AI-Micro-Drama-Generator](https://github.com/Anil-matcha/Open-AI-Micro-Drama-Generator) ★520 - Agent pipeline that makes a short drama video from an idea or script. ⚠️ no license ([write-up](https://openmicrodrama.com/projects/anil-matcha-open-ai-micro-drama-generator))
- [novanova-studio](https://github.com/Swayingleaves/novanova-studio) ★392 - Put AI image and video jobs on one infinite canvas. ([write-up](https://openmicrodrama.com/projects/swayingleaves-novanova-studio))
- [pai-code](https://github.com/Utopai-Research/pai-code) ★347 - A film studio on your laptop, run by Claude Code or Codex. ⚠️ NOASSERTION ([write-up](https://openmicrodrama.com/projects/utopai-research-pai-code))
- [novelvids](https://github.com/Anning01/novelvids) ★337 - Writes storyboards and video from a novel or a reference clip. ⚠️ CC-BY-NC-4.0 ([write-up](https://openmicrodrama.com/projects/anning01-novelvids))
- [ai-shotlive](https://github.com/sorker/ai-shotlive) ★330 - Server pipeline that turns a .txt novel into episode scripts and clips. ⚠️ CC-BY-NC-SA-4.0 ([write-up](https://openmicrodrama.com/projects/sorker-ai-shotlive))
- [Kinema](https://github.com/chillzhuang/Kinema) ★237 - Give it a topic or novel chapter, get a finished AI film. ([write-up](https://openmicrodrama.com/projects/chillzhuang-kinema))
- [ZJT](https://github.com/jeffstric/ZJT) ★224 - A storyboard and short-drama video from a script idea, built by AI agents. ⚠️ NOASSERTION ([write-up](https://openmicrodrama.com/projects/jeffstric-zjt))
- [xiakeman-ai-short-drama](https://github.com/XiakeMan777/xiakeman-ai-short-drama) ★196 - Builds characters, storyboards, images and clips from your novel or script. ⚠️ PolyForm-Noncommercial-1.0.0 ([write-up](https://openmicrodrama.com/projects/xiakeman777-xiakeman-ai-short-drama))

## Agent skill collections

Skill packs for Claude Code, Codex, Cursor and other coding agents.

- [shuohao-skills](https://github.com/eternityspring/shuohao-skills) ★4.0k - Pre-production assets for an AI short drama, straight from a novel. ([write-up](https://openmicrodrama.com/projects/eternityspring-shuohao-skills))
- [drama-skills](https://github.com/zenstory-ai/drama-skills) ★2.4k - Chains eleven agent skills into your whole AI short-drama pipeline. ([write-up](https://openmicrodrama.com/projects/zenstory-ai-drama-skills))
- [story-to-handdrawn-video](https://github.com/gnipbao/story-to-handdrawn-video) ★2.1k - Agent skill that makes a hand-drawn 3:4 video from a story or images. ([write-up](https://openmicrodrama.com/projects/gnipbao-story-to-handdrawn-video))
- [manju-laoli-skill](https://github.com/lixiaoxiao9888-create/manju-laoli-skill) ★982 - Feed it a script and it locks assets, storyboards and model prompts. ([write-up](https://openmicrodrama.com/projects/lixiaoxiao9888-create-manju-laoli-skill))
- [video-recap-skills](https://github.com/zenstory-ai/video-recap-skills) ★542 - A Chinese narration recap plus an editable JianYing draft. ([write-up](https://openmicrodrama.com/projects/zenstory-ai-video-recap-skills))
- [visual-skills](https://github.com/smixs/visual-skills) ★462 - Writes video and image prompts for Seedance, Kling and Veo. ([write-up](https://openmicrodrama.com/projects/smixs-visual-skills))
- [OnlyShot](https://github.com/A-cat-with-carrots/OnlyShot) ★298 - Claude Code skill that takes one idea to a full Chinese short drama. ([write-up](https://openmicrodrama.com/projects/a-cat-with-carrots-onlyshot))
- [short-drama-production](https://github.com/suihe1/short-drama-production) ★171 - Take a short drama from outline to QC inside Codex. ([write-up](https://openmicrodrama.com/projects/suihe1-short-drama-production))
- [director-skills](https://github.com/kangarooking/director-skills) ★158 - Director-style prompts for AI video shots, straight from your script. ([write-up](https://openmicrodrama.com/projects/kangarooking-director-skills))
- [workrally](https://github.com/Tencent/workrally) ★147 - Drives WorkRally's comic-drama image, video and canvas jobs from a terminal. ([write-up](https://openmicrodrama.com/projects/tencent-workrally))
- [film-studio-skills](https://github.com/machina-exm/film-studio-skills) ★142 - Agent skills that turn a script into locked, generation-ready shot prompts. ⚠️ no license ([write-up](https://openmicrodrama.com/projects/machina-exm-film-studio-skills))

## Script and story

Screenwriting, novel-to-script and episode-outline tools.

- [inkos](https://github.com/Narcooo/inkos) ★10k - Writes long novels, short stories, scripts and storyboards. ([write-up](https://openmicrodrama.com/projects/narcooo-inkos))
- [webnovel-writer](https://github.com/lingfengQAQ/webnovel-writer) ★7.3k - Claude Code plugin for long Chinese web novels that stay consistent. ([write-up](https://openmicrodrama.com/projects/lingfengqaq-webnovel-writer))
- [oh-story-claudecode](https://github.com/zenstory-ai/oh-story-claudecode) ★7.2k - Drop 13 skills into your coding agent to write Chinese web novels. ([write-up](https://openmicrodrama.com/projects/zenstory-ai-oh-story-claudecode))
- [AI_NovelGenerator](https://github.com/YILING0013/AI_NovelGenerator) ★6.1k - Long novels chapter by chapter from your own LLM API key. ([write-up](https://openmicrodrama.com/projects/yiling0013-ai-novelgenerator))
- [chinese-novelist-skill](https://github.com/PenglongHuang/chinese-novelist-skill) ★3.3k - Drafts a full Chinese novel chapter by chapter from a short Q&A. ([write-up](https://openmicrodrama.com/projects/penglonghuang-chinese-novelist-skill))
- [AI-Novel-Writing-Assistant](https://github.com/ExplosiveCoderflome/AI-Novel-Writing-Assistant) ★3.1k - Open-source workbench that writes full novels, comic panels and short-drama drafts. ([write-up](https://openmicrodrama.com/projects/explosivecoderflome-ai-novel-writing-assistant))
- [screenwriting-skills](https://github.com/jtydhr88/screenwriting-skills) ★1.5k - 26 screenwriting skills for film, TV and stage in Claude Code and Codex. ([write-up](https://openmicrodrama.com/projects/jtydhr88-screenwriting-skills))
- [short-drama](https://github.com/0xsline/short-drama) ★1.3k - Premise in, full short-drama script out, episode by episode. ([write-up](https://openmicrodrama.com/projects/0xsline-short-drama))
- [shanyin-screenwriting-master](https://github.com/Shanyin-ai/shanyin-screenwriting-master) ★1.2k - Scripts from a story idea, from 1-minute shorts to full series. ([write-up](https://openmicrodrama.com/projects/shanyin-ai-shanyin-screenwriting-master))
- [AI-automatically-generates-novels](https://github.com/wfcz10086/AI-automatically-generates-novels) ★958 - Chains one idea into a novel, short-drama script or storyboard. ([write-up](https://openmicrodrama.com/projects/wfcz10086-ai-automatically-generates-novels))
- [AI-drama-pound](https://github.com/POUND0423/AI-drama-pound) ★560 - Codex skill that writes Traditional Chinese vertical short-drama scripts. ([write-up](https://openmicrodrama.com/projects/pound0423-ai-drama-pound))
- [oh-story-dsh](https://github.com/zenstory-ai/oh-story-dsh) ★431 - Open novel, short-drama, game and video-recap workbenches in DeepSeek Harness. ([write-up](https://openmicrodrama.com/projects/zenstory-ai-oh-story-dsh))
- [short-drama-factory](https://github.com/lixiaoxiao9888-create/short-drama-factory) ★251 - A full short-drama script from one idea or a web novel, with paywall hooks. ([write-up](https://openmicrodrama.com/projects/lixiaoxiao9888-create-short-drama-factory))

## Storyboards and consistency

Shot lists, storyboards and tools that keep a character's face the same.

- [StoryDiffusion](https://github.com/HVision-NKU/StoryDiffusion) ★6.5k - Draws comic panels and long videos with the same character. ([write-up](https://openmicrodrama.com/projects/hvision-nku-storydiffusion))
- [Seedance2-Storyboard-Generator](https://github.com/liangdabiao/Seedance2-Storyboard-Generator) ★2.5k - Agent skill that turns a novel into a multi-episode Seedance 2.0 storyboard script. ⚠️ no license ([write-up](https://openmicrodrama.com/projects/liangdabiao-seedance2-storyboard-generator))
- [aimangastudio](https://github.com/morsoli/aimangastudio) ★1.5k - Type a story idea, get laid-out manga pages with AI. ([write-up](https://openmicrodrama.com/projects/morsoli-aimangastudio))
- [StoryGen-Atelier](https://github.com/0xsline/StoryGen-Atelier) ★986 - Storyboards from a story idea, then one video from AI clips. ([write-up](https://openmicrodrama.com/projects/0xsline-storygen-atelier))
- [CozyClay](https://github.com/NomaDamas/CozyClay) ★746 - 3D blocking and camera moves, exported as keyframe packs for AI video. ([write-up](https://openmicrodrama.com/projects/nomadamas-cozyclay))
- [OmniChar](https://github.com/omnichar/OmniChar) ★463 - Keeps one character file you reuse across AI image and video models. ([write-up](https://openmicrodrama.com/projects/omnichar-omnichar))
- [open-storyboard-canvas](https://github.com/ganbo-gab/open-storyboard-canvas) ★362 - Local node canvas for AI storyboards, image and video generation. ([write-up](https://openmicrodrama.com/projects/ganbo-gab-open-storyboard-canvas))
- [motion-previs-studio](https://github.com/wassermanproductions/motion-previs-studio) ★361 - Feed it a reference shot, get pose, depth and camera-move files. ([write-up](https://openmicrodrama.com/projects/wassermanproductions-motion-previs-studio))
- [agent-storyboard](https://github.com/Yuuhann1999/agent-storyboard) ★350 - A storyboard table your agent fills in, shot by shot. ([write-up](https://openmicrodrama.com/projects/yuuhann1999-agent-storyboard))
- [director-desk](https://github.com/mangfufu/director-desk) ★325 - Blocks out scenes in 3D, then exports a reference video and prompts. ([write-up](https://openmicrodrama.com/projects/mangfufu-director-desk))
- [story-shot-agent](https://github.com/neopen/story-shot-agent) ★209 - Agent skill that turns a script into shot-by-shot video prompts. ([write-up](https://openmicrodrama.com/projects/neopen-story-shot-agent))
- [3d-director-desk](https://github.com/xiaozangao/3d-director-desk) ★191 - Place characters, walk the camera with WASD, save shots in your browser. ([write-up](https://openmicrodrama.com/projects/xiaozangao-3d-director-desk))
- [ai-visual-director](https://github.com/jijiutong/ai-visual-director) ★176 - Character sheets, storyboards and video prompts from one written story. ([write-up](https://openmicrodrama.com/projects/jijiutong-ai-visual-director))
- [h3-storyboard-skill](https://github.com/phileiny/h3-storyboard-skill) ★171 - Cuts a script into MiniMax H3 shots that keep faces moving. ([write-up](https://openmicrodrama.com/projects/phileiny-h3-storyboard-skill))
- [DirectorSKILL](https://github.com/wuwangzhang1216/DirectorSKILL) ★145 - Claude Code skill that turns a script or one keyframe into a shot plan. ([write-up](https://openmicrodrama.com/projects/wuwangzhang1216-directorskill))

## Prompt collections

Prompt libraries for Seedance, Kling, Veo, Hailuo, Wan and others.

- [seedance-2.0](https://github.com/Emily2040/seedance-2.0) ★7.5k - Agent skills that turn a rough idea into a shot-by-shot Seedance 2.0 prompt. ([write-up](https://openmicrodrama.com/projects/emily2040-seedance-2-0))
- [seedance2-skill](https://github.com/dexhunter/seedance2-skill) ★4.1k - Prompt templates for Seedance 2.0, ready for your AI agent. ([write-up](https://openmicrodrama.com/projects/dexhunter-seedance2-skill))
- [seedance-prompt-skill](https://github.com/songguoxs/seedance-prompt-skill) ★2.9k - Describe your idea, get Chinese Seedance 2.0 prompts in Claude Code. ⚠️ no license ([write-up](https://openmicrodrama.com/projects/songguoxs-seedance-prompt-skill))
- [awesome-seedance](https://github.com/ZeroLu/awesome-seedance) ★2.6k - Prompt library for Seedance 2.0: cinematic, anime, UGC and short-drama shots. ([write-up](https://openmicrodrama.com/projects/zerolu-awesome-seedance))
- [awesome-seedance-2-prompts](https://github.com/YouMind-OpenLab/awesome-seedance-2-prompts) ★2.1k - Puts 6,459 Seedance 2.0 prompts in one list, plus a web gallery. ([write-up](https://openmicrodrama.com/projects/youmind-openlab-awesome-seedance-2-prompts))
- [awesome-seedance](https://github.com/LearnPrompt/awesome-seedance) ★1.6k - Gives you 25 Seedance prompt templates, each checked against its original post. ([write-up](https://openmicrodrama.com/projects/learnprompt-awesome-seedance))
- [make-prompt-seedance2](https://github.com/liangdabiao/make-prompt-seedance2) ★686 - Template pack and agent skill for prompting Seedance 2.0. ⚠️ no license ([write-up](https://openmicrodrama.com/projects/liangdabiao-make-prompt-seedance2))
- [higgsfield-ai-prompt-skill](https://github.com/OSideMedia/higgsfield-ai-prompt-skill) ★670 - Higgsfield AI video and image prompts, written by Claude. ([write-up](https://openmicrodrama.com/projects/osidemedia-higgsfield-ai-prompt-skill))
- [prompt-lens](https://github.com/raojiacui/prompt-lens) ★600 - A reusable AI video prompt from any clip you upload. ([write-up](https://openmicrodrama.com/projects/raojiacui-prompt-lens))
- [zy-cinematic-realism](https://github.com/popopo-99/zy-cinematic-realism) ★523 - Plans a scene into a locked visual plan and native model prompts. ⚠️ CC-BY-NC-4.0 ([write-up](https://openmicrodrama.com/projects/popopo-99-zy-cinematic-realism))
- [ai-shortfilm-prompts](https://github.com/jnMetaCode/ai-shortfilm-prompts) ★448 - Prompt system that turns ideas into cinematic Sora, Kling, Veo or Seedance prompts. ([write-up](https://openmicrodrama.com/projects/jnmetacode-ai-shortfilm-prompts))
- [awesome-MiniMax-H3-cases](https://github.com/SkyNotSilent/awesome-MiniMax-H3-cases) ★415 - Play 2112 MiniMax H3 video cases, with 663 public prompts and 25 setup guides. ([write-up](https://openmicrodrama.com/projects/skynotsilent-awesome-minimax-h3-cases))
- [seedance-2-5-video-director](https://github.com/liyue-aigc/seedance-2-5-video-director) ★402 - A Seedance 2.5 director plan and paste-ready prompt from your idea. ([write-up](https://openmicrodrama.com/projects/liyue-aigc-seedance-2-5-video-director))
- [seedance-prompt](https://github.com/zhouwei713/seedance-prompt) ★328 - Writes realistic AI video prompts with device flaws and a 10-15 second timeline. ([write-up](https://openmicrodrama.com/projects/zhouwei713-seedance-prompt))
- [minimax-h3-prompt-composer](https://github.com/BMB12d3/minimax-h3-prompt-composer) ★290 - One HTML file that builds checked MiniMax H3 video prompts. ⚠️ no license ([write-up](https://openmicrodrama.com/projects/bmb12d3-minimax-h3-prompt-composer))
- [post-production-skill](https://github.com/huangbai-AI/post-production-skill) ★250 - Retro-studio VFX prompts for Seedance 2.5, from a plain idea. ⚠️ no license ([write-up](https://openmicrodrama.com/projects/huangbai-ai-post-production-skill))
- [video-prompting-skill](https://github.com/Square-Zero-Labs/video-prompting-skill) ★178 - Video-model prompts and character sheets for your AI agent. ([write-up](https://openmicrodrama.com/projects/square-zero-labs-video-prompting-skill))
- [Seedance-ShotDesign-Skills](https://github.com/woodfantasy/Seedance-ShotDesign-Skills) ★119 - Writes checked Seedance 2.5 shot prompts from a rough idea. ([write-up](https://openmicrodrama.com/projects/woodfantasy-seedance-shotdesign-skills))

## ComfyUI workflows

Ready-made node workflows for video, lip sync and consistent characters.

- [ComfyUI-WanVideoWrapper](https://github.com/kijai/ComfyUI-WanVideoWrapper) ★6.7k - Puts WanVideo and related video models inside ComfyUI. ([write-up](https://openmicrodrama.com/projects/kijai-comfyui-wanvideowrapper))
- [ComfyUI-LTXVideo](https://github.com/Lightricks/ComfyUI-LTXVideo) ★4.2k - Gives ComfyUI extra nodes and example workflows for the LTX-2 video model. ⚠️ NOASSERTION ([write-up](https://openmicrodrama.com/projects/lightricks-comfyui-ltxvideo))
- [ComfyUI-SeedVR2_VideoUpscaler](https://github.com/numz/ComfyUI-SeedVR2_VideoUpscaler) ★2.9k - SeedVR2 video and image upscaling, as ComfyUI nodes or a CLI. ([write-up](https://openmicrodrama.com/projects/numz-comfyui-seedvr2-videoupscaler))
- [HeliosGen](https://github.com/SegFault42/HeliosGen) ★2.3k - AI image and video pipelines on a local node canvas. ⚠️ no license ([write-up](https://openmicrodrama.com/projects/segfault42-heliosgen))
- [ComfyUI-VideoHelperSuite](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite) ★1.9k - Loads video as frames in ComfyUI, then writes them back out as video. ([write-up](https://openmicrodrama.com/projects/kosinkadink-comfyui-videohelpersuite))
- [ComfyUI_VNCCS](https://github.com/AHEKOT/ComfyUI_VNCCS) ★1.6k - ComfyUI nodes for matching character sprites in visual novels. ([write-up](https://openmicrodrama.com/projects/ahekot-comfyui-vnccs))
- [workflow_templates](https://github.com/Comfy-Org/workflow_templates) ★1.2k - Browse official ComfyUI workflow templates and subgraph blueprints. ([write-up](https://openmicrodrama.com/projects/comfy-org-workflow-templates))
- [ComfyUI-H3-Motion-Context](https://github.com/NikoDemon80/ComfyUI-H3-Motion-Context) ★1.0k - Longer MiniMax H3 sequences with motion and sound carried across cuts. ([write-up](https://openmicrodrama.com/projects/nikodemon80-comfyui-h3-motion-context))
- [ComfyUI-MiniMaxH3-Easy](https://github.com/nkxx188/ComfyUI-MiniMaxH3-Easy) ★798 - A few ComfyUI nodes for MiniMax H3 video, with less hand-wiring. ([write-up](https://openmicrodrama.com/projects/nkxx188-comfyui-minimaxh3-easy))
- [comfyui-vrgamedevgirl](https://github.com/vrgamegirl19/comfyui-vrgamedevgirl) ★740 - Plans, generates and fixes AI video scenes in ComfyUI. ⚠️ NOASSERTION ([write-up](https://openmicrodrama.com/projects/vrgamegirl19-comfyui-vrgamedevgirl))
- [ComfyUI-MiniMaxH3-TimelineDirector](https://github.com/Songssx/ComfyUI-MiniMaxH3-TimelineDirector) ★541 - ComfyUI nodes for editing a reference-media timeline in MiniMax H3. ([write-up](https://openmicrodrama.com/projects/songssx-comfyui-minimaxh3-timelinedirector))
- [ComfyUI-WanAnimatePlus](https://github.com/wuwukaka/ComfyUI-WanAnimatePlus) ★417 - Adds up to 5 extra reference photos and smooth joins to Wan Animate. ([write-up](https://openmicrodrama.com/projects/wuwukaka-comfyui-wananimateplus))
- [ComfyUI-MiniMaxH3-Director](https://github.com/seesee75-commits/ComfyUI-MiniMaxH3-Director) ★305 - Gives MiniMax H3 a ComfyUI timeline: shots, keyframes, audio. ([write-up](https://openmicrodrama.com/projects/seesee75-commits-comfyui-minimaxh3-director))
- [ComfyUI-MiniMax-H3-Promptor](https://github.com/1038lab/ComfyUI-MiniMax-H3-Promptor) ★241 - Writes MiniMax H3 video prompts from your images, video and audio. ([write-up](https://openmicrodrama.com/projects/1038lab-comfyui-minimax-h3-promptor))
- [ComfyUI-OrbitSheets](https://github.com/lumosai8/ComfyUI-OrbitSheets) ★72 - ComfyUI nodes for character and location reference sheets from one camera move. ([write-up](https://openmicrodrama.com/projects/lumosai8-comfyui-orbitsheets))

## Editing, voice and audio

Cutting, captions, dubbing, voice cloning, lip sync and upscaling.

- [GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS) ★62k - Clones a voice from a 5-second clip and reads your text in it. ([write-up](https://openmicrodrama.com/projects/rvc-boss-gpt-sovits))
- [index-tts](https://github.com/index-tts/index-tts) ★24k - Voice cloner that reads your script in five languages. ⚠️ NOASSERTION ([write-up](https://openmicrodrama.com/projects/index-tts-index-tts))
- [video2x](https://github.com/k4yt3x/video2x) ★22k - Makes small video bigger and smoother using Anime4K, Real-ESRGAN, RIFE. ([write-up](https://openmicrodrama.com/projects/k4yt3x-video2x))
- [pyvideotrans](https://github.com/jianchang512/pyvideotrans) ★19k - Video translated, subtitled and dubbed into another language. ([write-up](https://openmicrodrama.com/projects/jianchang512-pyvideotrans))
- [LivePortrait](https://github.com/KlingAIResearch/LivePortrait) ★19k - Animates a face photo or video with motion from another clip. ([write-up](https://openmicrodrama.com/projects/klingairesearch-liveportrait))
- [VideoLingo](https://github.com/Huanshere/VideoLingo) ★19k - Translated subtitles and a dubbed voice track for any video. ([write-up](https://openmicrodrama.com/projects/huanshere-videolingo))
- [video-subtitle-remover](https://github.com/YaoFANGUK/video-subtitle-remover) ★13k - Desktop app that erases burned-in subtitles and text watermarks. ([write-up](https://openmicrodrama.com/projects/yaofanguk-video-subtitle-remover))
- [NarratoAI](https://github.com/linyqh/NarratoAI) ★11k - Feed it a film or drama, get a narrated commentary video. ([write-up](https://openmicrodrama.com/projects/linyqh-narratoai))
- [InfiniteTalk](https://github.com/MeiGen-AI/InfiniteTalk) ★8.0k - Lip-synced video or photo from new audio, any length. ([write-up](https://openmicrodrama.com/projects/meigen-ai-infinitetalk))
- [LatentSync](https://github.com/bytedance/LatentSync) ★6.1k - Re-syncs a talking-face video to another audio track. ([write-up](https://openmicrodrama.com/projects/bytedance-latentsync))
- [YouDub-webui](https://github.com/liuzhao1225/YouDub-webui) ★5.6k - Desktop app that dubs a YouTube or Bilibili video into another language. ([write-up](https://openmicrodrama.com/projects/liuzhao1225-youdub-webui))
- [SmartSub](https://github.com/buxuku/SmartSub) ★5.4k - Feed it a video, get subtitles, translations and AI dubbing. ([write-up](https://openmicrodrama.com/projects/buxuku-smartsub))
- [pyJianYingDraft](https://github.com/GuanYixuan/pyJianYingDraft) ★4.5k - JianYing draft files from Python, so you can script your edits. ([write-up](https://openmicrodrama.com/projects/guanyixuan-pyjianyingdraft))
- [jianying-editor-skill](https://github.com/luoluoluo22/jianying-editor-skill) ★3.7k - Drives JianYing Pro: builds drafts, adds voiceover and subtitles. ([write-up](https://openmicrodrama.com/projects/luoluoluo22-jianying-editor-skill))
- [FireRed-OpenStoryline](https://github.com/FireRedTeam/FireRed-OpenStoryline) ★3.5k - Agent that edits video by chat, planning cuts, music and narration. ([write-up](https://openmicrodrama.com/projects/fireredteam-firered-openstoryline))
- [chengfeng-videocut-skills](https://github.com/Agentchengfeng/chengfeng-videocut-skills) ★3.0k - Install this in Codex CLI, then cut, subtitle, overlay and export video. ([write-up](https://openmicrodrama.com/projects/agentchengfeng-chengfeng-videocut-skills))
- [REAL-Video-Enhancer](https://github.com/TNTwise/REAL-Video-Enhancer) ★2.3k - Higher frame rate and resolution for video on your own PC. ([write-up](https://openmicrodrama.com/projects/tntwise-real-video-enhancer))
- [MMAudio](https://github.com/hkchengrex/MMAudio) ★2.3k - Makes sound effects and ambience that match your video. ([write-up](https://openmicrodrama.com/projects/hkchengrex-mmaudio))
- [VectCutAPI](https://github.com/sun-guannan/VectCutAPI) ★2.3k - API and MCP server for turning AI clips into CapCut and Jianying drafts. ([write-up](https://openmicrodrama.com/projects/sun-guannan-vectcutapi))
- [capcut-mate](https://github.com/Hommy-master/capcut-mate) ★1.9k - Call an API to build Jianying or CapCut drafts and render video. ([write-up](https://openmicrodrama.com/projects/hommy-master-capcut-mate))
- [MOSS-TTSD](https://github.com/OpenMOSS/MOSS-TTSD) ★1.4k - Cloned-voice dialogue audio for 1 to 5 speakers. ([write-up](https://openmicrodrama.com/projects/openmoss-moss-ttsd))
- [SonicVale](https://github.com/xcLee001/SonicVale) ★628 - Dubs novels and scripts with multi-character AI voices. ([write-up](https://openmicrodrama.com/projects/xclee001-sonicvale))
- [X-Dub](https://github.com/KlingAIResearch/X-Dub) ★235 - Tool that redraws a video character's mouth to match a new audio track. ([write-up](https://openmicrodrama.com/projects/klingairesearch-x-dub))
- [fablr](https://github.com/Agions/fablr) ★157 - Commentary scripts and CapCut drafts from long footage. ([write-up](https://openmicrodrama.com/projects/agions-fablr))

## Video agents and frameworks

General AI video pipelines you can bend into a drama workflow.

- [MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) ★128k - Writes a narrated short video from a topic: script, voiceover, footage, subtitles. ([write-up](https://openmicrodrama.com/projects/harry0703-moneyprinterturbo))
- [OpenMontage](https://github.com/calesthio/OpenMontage) ★62k - Video studio that your AI coding assistant runs. ([write-up](https://openmicrodrama.com/projects/calesthio-openmontage))
- [Pixelle-Video](https://github.com/ATH-MaaS/Pixelle-Video) ★29k - Type one topic and get a narrated short video: script, images, voice, music. ([write-up](https://openmicrodrama.com/projects/ath-maas-pixelle-video))
- [hypit](https://github.com/hypit-ai/hypit) ★18k - A language that lets your coding agent clone and re-run short videos. ⚠️ NOASSERTION ([write-up](https://openmicrodrama.com/projects/hypit-ai-hypit))
- [ViMax](https://github.com/HKUDS/ViMax) ★13k - Multi-shot AI video from an idea, a script, or a novel chapter. ([write-up](https://openmicrodrama.com/projects/hkuds-vimax))
- [OpenCreator](https://github.com/krillinai/OpenCreator) ★13k - Dubs, translates and writes short-video scripts on your own machine. ([write-up](https://openmicrodrama.com/projects/krillinai-opencreator))
- [Pallaidium](https://github.com/tin2tin/Pallaidium) ★1.5k - Blender add-on that runs AI image, video and voice models on your timeline. ([write-up](https://openmicrodrama.com/projects/tin2tin-pallaidium))
- [Maestro](https://github.com/Blizaine/Maestro) ★680 - One prompt in: a local LLM plans shots, writes lyrics and makes clips. ⚠️ NOASSERTION ([write-up](https://openmicrodrama.com/projects/blizaine-maestro))
- [Orkas-VideoStudio](https://github.com/Orkas-AI/Orkas-VideoStudio) ★497 - Editable video plans from a plain-language brief, rendered by your coding agent. ([write-up](https://openmicrodrama.com/projects/orkas-ai-orkas-videostudio))
- [agnes-video-generator](https://github.com/lcy362/agnes-video-generator) ★449 - Writes a narrated, subtitled multi-scene video from a text idea or long article. ([write-up](https://openmicrodrama.com/projects/lcy362-agnes-video-generator))
- [AI_novel](https://github.com/tyxben/AI_novel) ★281 - Desktop app that turns novel text or one idea into subtitled short videos. ([write-up](https://openmicrodrama.com/projects/tyxben-ai-novel))
- [KupkaProd-Cinema-Pipeline](https://github.com/Matticusnicholas/KupkaProd-Cinema-Pipeline) ★204 - Feed it a prompt or screenplay, get a finished video on your PC. ⚠️ NOASSERTION ([write-up](https://openmicrodrama.com/projects/matticusnicholas-kupkaprod-cinema-pipeline))
- [Vibefilming](https://github.com/wangzai-double-milk/Vibefilming) ★163 - A finished short film from one plain sentence, with AI review and reshoots. ([write-up](https://openmicrodrama.com/projects/wangzai-double-milk-vibefilming))

## Model tooling

API clients, SDKs and local runners for one specific video model.

- [Wan2.2](https://github.com/Wan-Video/Wan2.2) ★18k - Open video models for text, image, speech and character animation. ([write-up](https://openmicrodrama.com/projects/wan-video-wan2-2))
- [FramePack](https://github.com/lllyasviel/FramePack) ★17k - Animates a still image into a longer video on your own GPU. ([write-up](https://openmicrodrama.com/projects/lllyasviel-framepack))
- [DiffSynth-Studio](https://github.com/modelscope/DiffSynth-Studio) ★13k - Trains and runs image, video and audio diffusion models on your own GPU. ([write-up](https://openmicrodrama.com/projects/modelscope-diffsynth-studio))
- [Wan2GP](https://github.com/deepbeepmeep/Wan2GP) ★9.8k - Desktop app that runs open video, image and audio models on your own PC. ⚠️ NOASSERTION ([write-up](https://openmicrodrama.com/projects/deepbeepmeep-wan2gp))
- [LTX-2](https://github.com/Lightricks/LTX-2) ★9.6k - Open audio-video model you run yourself on a CUDA GPU. ⚠️ NOASSERTION ([write-up](https://openmicrodrama.com/projects/lightricks-ltx-2))
- [SkyReels-V2](https://github.com/SkyworkAI/SkyReels-V2) ★7.6k - Makes long, even endless clips with open SkyReels-V2 video models. ⚠️ NOASSERTION ([write-up](https://openmicrodrama.com/projects/skyworkai-skyreels-v2))
- [HunyuanVideo-1.5](https://github.com/Tencent-Hunyuan/HunyuanVideo-1.5) ★4.6k - Open 8.3B video model for text-to-video and image-to-video. ⚠️ NOASSERTION ([write-up](https://openmicrodrama.com/projects/tencent-hunyuan-hunyuanvideo-1-5))
- [FastVideo](https://github.com/hao-ai-lab/FastVideo) ★4.5k - Trains and speeds up open video models on your own GPU. ([write-up](https://openmicrodrama.com/projects/hao-ai-lab-fastvideo))
- [open-higgsfield](https://github.com/wide-trace/open-higgsfield) ★3.9k - Self-hosted studio for 38 image and video models. ⚠️ no license ([write-up](https://openmicrodrama.com/projects/wide-trace-open-higgsfield))
- [LightX2V](https://github.com/ModelTC/LightX2V) ★2.9k - Loads open image and video models onto your own GPU. ([write-up](https://openmicrodrama.com/projects/modeltc-lightx2v))
- [VideoX-Fun](https://github.com/aigc-apps/VideoX-Fun) ★2.3k - Python toolkit that makes AI video and trains your own models. ([write-up](https://openmicrodrama.com/projects/aigc-apps-videox-fun))
- [cli](https://github.com/MiniMax-AI/cli) ★2.2k - MiniMax images, video, speech and text from your terminal. ⚠️ no license ([write-up](https://openmicrodrama.com/projects/minimax-ai-cli))
- [LTX-Desktop](https://github.com/Lightricks/LTX-Desktop) ★2.0k - Local LTX video generation and editing on your desktop. ([write-up](https://openmicrodrama.com/projects/lightricks-ltx-desktop))
- [MiniMax-MCP](https://github.com/MiniMax-AI/MiniMax-MCP) ★1.6k - Plugs MiniMax speech, voice cloning, image and video tools into your MCP client. ([write-up](https://openmicrodrama.com/projects/minimax-ai-minimax-mcp))
- [Stand-In](https://github.com/WeChatCV/Stand-In) ★791 - Wan add-on that keeps one face consistent across shots. ([write-up](https://openmicrodrama.com/projects/wechatcv-stand-in))
- [StoryMem](https://github.com/Kevin-thu/StoryMem) ★771 - Give it a shot list, get a minute-long multi-shot video. ⚠️ NOASSERTION ([write-up](https://openmicrodrama.com/projects/kevin-thu-storymem))
- [cli](https://github.com/higgsfield-ai/cli) ★621 - 40+ Higgsfield image, video, 3D and audio models from your terminal. ([write-up](https://openmicrodrama.com/projects/higgsfield-ai-cli))
- [video-generator-client](https://github.com/letorig/video-generator-client) ★551 - Puts Seedance, Kling, MiniMax and Wan video models behind one Python tool. ([write-up](https://openmicrodrama.com/projects/letorig-video-generator-client))
- [ltx-video-mac](https://github.com/james-see/ltx-video-mac) ★423 - Mac app that renders AI video with sound using LTX and MiniMax. ([write-up](https://openmicrodrama.com/projects/james-see-ltx-video-mac))
- [Wan-Animate-2](https://github.com/Wan-Video/Wan-Animate-2) ★331 - Animated clips from one character photo and a driving video. ([write-up](https://openmicrodrama.com/projects/wan-video-wan-animate-2))
- [Phosphene](https://github.com/mrbizarro/Phosphene) ★242 - Video, image and music models on your Mac, no cloud or API keys. ([write-up](https://openmicrodrama.com/projects/mrbizarro-phosphene))
- [ShotStream](https://github.com/KlingAIResearch/ShotStream) ★185 - Chains multi-shot video frames on the fly for interactive stories. ⚠️ no license ([write-up](https://openmicrodrama.com/projects/klingairesearch-shotstream))

## Datasets and papers

Benchmarks and research code for story video and long-form consistency.

- [Awesome-Video-Diffusion](https://github.com/showlab/Awesome-Video-Diffusion) ★5.8k - Video diffusion papers and projects, sorted into labeled sections. ⚠️ no license ([write-up](https://openmicrodrama.com/projects/showlab-awesome-video-diffusion))
- [VBench](https://github.com/Vchitect/VBench) ★1.8k - Scores video generation models on quality, faithfulness and safety. ([write-up](https://openmicrodrama.com/projects/vchitect-vbench))
- [awesome-video-generation](https://github.com/AlonzoLeeeooo/awesome-video-generation) ★786 - A paper index for video generation, sorted by task and year. ([write-up](https://openmicrodrama.com/projects/alonzoleeeooo-awesome-video-generation))
- [Awesome-Story-Generation](https://github.com/yingpengma/Awesome-Story-Generation) ★660 - Browse 199 papers on AI story generation and screenplays. ([write-up](https://openmicrodrama.com/projects/yingpengma-awesome-story-generation))
- [awesome-ltx2](https://github.com/wildminder/awesome-ltx2) ★597 - LTX-2 checkpoints, text encoders, LoRAs and ComfyUI workflows in one list. ⚠️ no license ([write-up](https://openmicrodrama.com/projects/wildminder-awesome-ltx2))
- [awesome-claude-video-skills](https://github.com/zhuyansen/awesome-claude-video-skills) ★347 - Grades 204 agent skills that let coding agents make video. ([write-up](https://openmicrodrama.com/projects/zhuyansen-awesome-claude-video-skills))
- [awesome-ai-media-cn](https://github.com/JuneYaooo/awesome-ai-media-cn) ★267 - A Chinese-language index of open-source AI video and short-drama tools. ([write-up](https://openmicrodrama.com/projects/juneyaooo-awesome-ai-media-cn))
- [SkyScript-100M](https://github.com/vaew/SkyScript-100M) ★150 - Research dataset of 1B short-drama script and shooting-script pairs (sample only). ([write-up](https://openmicrodrama.com/projects/vaew-skyscript-100m))
- [ai-short-drama-resources](https://github.com/kangarooking/ai-short-drama-resources) ★51 - Index of AI short-drama and comic-drama courses, in Chinese. ([write-up](https://openmicrodrama.com/projects/kangarooking-ai-short-drama-resources))

## Individual agent skills

Single skills pulled out of the collections above, grouped by production stage. Install steps for each agent are on [OpenMicroDrama](https://openmicrodrama.com/skills).

**Script**

- [Novel Outline](https://github.com/eternityspring/shuohao-skills/tree/HEAD/skills/novel-outline) - Turns a novel into a short-drama outline: episode summaries, a hook per episode, a cast list and a prop list. A script checks the outline against 14 rules.
- [Novel Analyze](https://github.com/zenstory-ai/drama-skills/tree/HEAD/skills/short-drama-novel-analyze) - Samples a long novel to see if it's worth adapting. It indexes the chapters and suggests which parts could become episodes.
- [Episode Writer](https://github.com/zenstory-ai/drama-skills/tree/HEAD/skills/short-drama-write) - Writes one episode at a time: the episode goal, beats that lead into each other, and a script you can actually shoot.
- [Produce Anime](https://github.com/zhaihao118/Micro-Drama-Skills/tree/HEAD/.claude/skills/produce-anime) - Writes a whole 25-episode micro drama: scripts, a character bible, six-panel storyboard images and storyboard settings for every episode.
- [Series Structure](https://github.com/jtydhr88/screenwriting-skills/tree/HEAD/plugins/screenwriting/skills/sw-series-structure) - Helps you shape a series: cold opens, act breaks, cliffhangers, A/B/C storylines and the arc of a whole season.
- [Dialogue](https://github.com/jtydhr88/screenwriting-skills/tree/HEAD/plugins/screenwriting/skills/sw-dialogue) - Helps you write dialogue that does something: what's said and left unsaid, how to slip in backstory, and common dialogue mistakes.
- [Short Drama Screenwriter](https://github.com/0xsline/short-drama/tree/HEAD/SKILL.md) - Writes micro-drama scripts from premise to finished episodes: story plan, characters and villain, outline, drafts, a quality check and a compliance check.
- [Short-Drama Screenwriter (Traditional Chinese)](https://github.com/POUND0423/AI-drama-pound/tree/HEAD/skill-src/ai-short-drama-screenwriter) - Writes and revises vertical short-drama scripts in Traditional Chinese: the brief, genre, episode structure, relationships and scene breakdowns.
- [Short-Drama Factory](https://github.com/lixiaoxiao9888-create/short-drama-factory/tree/HEAD/SKILL.md) - Plans serialized Douyin/Hongguo-style scripts. It sets the length format, genre and red lines first, then writes episodes in a fixed order.
- [Shanyin Screenwriting Master](https://github.com/Shanyin-ai/shanyin-screenwriting-master/tree/HEAD/screenwriting-master（Claude&GPT通用）.skill) - A single skill file for writing scripts in plain language, from short concepts to 90-minute films and series: characters, outlines, scenes and drafts.

**Character**

- [Novel Characters](https://github.com/eternityspring/shuohao-skills/tree/HEAD/skills/novel-characters) - Builds a character bible from the outline. Each person gets a profile, a look prompt, a voice prompt and character sheet images.
- [Character Refs](https://github.com/eternityspring/shuohao-skills/tree/HEAD/skills/character-refs) - Makes reference images for any character. It draws a front full-body shot first, then a headshot, side, back and close-up views that match it.
- [Drama Assets](https://github.com/zenstory-ai/drama-skills/tree/HEAD/skills/short-drama-assets) - Locks down characters, looks, locations and props, and notes what has to stay the same from shot to shot.
- [Asset Passport](https://github.com/machina-exm/film-studio-skills/tree/HEAD/skills/asset-passport) - Keeps asking questions until a character, place or prop is fully described. Then it writes reference-sheet prompts on a grey background.
- [Character Lock](https://github.com/jijiutong/ai-visual-director/tree/HEAD/sub-skills/character) - Locks a character's look (face, costume, props) so they stay the same in every shot of the storyboard.

**Storyboard**

- [Novel Storyboard](https://github.com/eternityspring/shuohao-skills/tree/HEAD/skills/novel-storyboard) - Cuts the script into 2–5 second shots, grouped into segments of up to 15 seconds, and exports shot packages for MiniMax H3 or Seedance.
- [Drama Storyboard](https://github.com/zenstory-ai/drama-skills/tree/HEAD/skills/short-drama-storyboard) - Plans each scene, writes the shot list and freezes the keyframe prompts. Every shot is tied back to the source text.
- [Seedance Storyboard Generator](https://github.com/liangdabiao/Seedance2-Storyboard-Generator/tree/HEAD/.claude/skills/seedance-storyboard-generator) - Turns a story into a four-act script, a numbered list of characters, scenes and props, and a Seedance 2.0 storyboard prompt for each episode.
- [Short-Drama Director (suihe1)](https://github.com/suihe1/short-drama-production/tree/HEAD/skills/short-drama-director) - Breaks each scene into staging, shot size, camera position and camera movement, ready for the storyboard step.
- [H3 Storyboard](https://github.com/phileiny/h3-storyboard-skill/tree/HEAD/skills/h3-storyboard) - Breaks a script into MiniMax H3 shot lists: counts beats, splits shots, orders facial expressions and picks camera moves and reference images.
- [Cinematic Director](https://github.com/wuwangzhang1216/DirectorSKILL/tree/HEAD/SKILL.md) - Turns a script or a keyframe into a full film plan: beats, blocking (where actors stand and move), shot lists, and keyframe and motion prompts.

**Prompting**

- [Drama Video Prompts](https://github.com/zenstory-ai/drama-skills/tree/HEAD/skills/short-drama-video-prompts) - Writes a video prompt for each shot: movement, acting between characters, camera, sound, and how the shot starts and ends.
- [Seedance 2.0 Prompt Guide](https://github.com/dexhunter/seedance2-skill/tree/HEAD/SKILL.md) - Teaches your agent to write Seedance 2.0 prompts: input limits, @ reference syntax, camera words and ready templates. Comes in English and Chinese.
- [Seedance Prompt Skill](https://github.com/songguoxs/seedance-prompt-skill/tree/HEAD/.claude/skills/seedance) - Turns a plain idea into a structured Chinese Seedance 2.0 prompt. Covers text-to-video, keeping a face from a reference image, and copying camera moves.
- [Video Director](https://github.com/smixs/visual-skills/tree/HEAD/video) - Writes video prompts the way a director would. It loads the rules for one model (Seedance, Kling or Veo) and returns one prompt or a multi-shot plan.
- [Shot Prompt](https://github.com/machina-exm/film-studio-skills/tree/HEAD/skills/shot-prompt) - Turns one shot card into a ready prompt built from 15 fixed blocks. It refuses to run while any asset in the frame is still a draft.
- [Higgsfield Seedance 2.5](https://github.com/OSideMedia/higgsfield-ai-prompt-skill/tree/HEAD/skills/higgsfield-seedance-2-5) - Writes Seedance 2.5 prompts for Higgsfield: its four generation modes, @Image/@Video/@Audio references and timestamp-based pacing.
- [Seedance 2.0 Skill OS](https://github.com/Emily2040/seedance-2.0/tree/HEAD/SKILL.md) - One root skill that turns a scene idea into a shot-by-shot Seedance 2.0 prompt plus a shot table, so you can check framing before you pay for a take.
- [Seedance 2.5 Video Director](https://github.com/liyue-aigc/seedance-2-5-video-director/tree/HEAD/SKILL.md) - Plans Seedance 2.5 videos: script, director plan and prompts. It keeps characters locked and helps with follow-on clips and transitions.
- [Action Fight Prompt](https://github.com/kangarooking/director-skills/tree/HEAD/action-fight-prompt) - Designs fight-scene prompts in timed segments, with cause and effect between moves and how the setting reacts. It writes prompts only.

**Video**

- [Generate Media](https://github.com/zhaihao118/Micro-Drama-Skills/tree/HEAD/.claude/skills/generate-media) - Calls the Gemini API to make character reference images, storyboard panels and video for a project or a range of episodes. Needs your own key.
- [PixVerse CLI](https://github.com/PixVerseAI/skills/tree/HEAD/skills/SKILL.md) - Teaches your agent the PixVerse CLI: text or image to video, character sheets, longer clips and upscaling. You need a PixVerse subscription.

**Editing**

- [Chengfeng Cut](https://github.com/Agentchengfeng/chengfeng-videocut-skills/tree/HEAD/plugins/chengfeng-videocut/skills/chengfeng-cut) - Cuts talking-head (口播) footage inside the chengfeng-videocut editor. You need the separate chengfeng-videocut app installed.
- [Video Recap](https://github.com/zenstory-ai/video-recap-skills/tree/HEAD/skills/video-recap) - Turns a film or episode into a Chinese narration recap video. It checks your setup, then runs the watch, script, cut, voice and assemble steps.
- [JianYing Editor](https://github.com/luoluoluo22/jianying-editor-skill/tree/HEAD/SKILL.md) - Lets your agent build and edit JianYing (CapCut China) drafts: import clips, add voice-over, subtitles, music, effects and keyframes.

**Review**

- [Drama Review](https://github.com/zenstory-ai/drama-skills/tree/HEAD/skills/short-drama-review) - Checks the structure and content of your episodes and tells you what to fix, based on what actually came out of production.

**Other**

- [Short-Drama Director (Laoli)](https://github.com/lixiaoxiao9888-create/manju-laoli-skill/tree/HEAD/short-drama-director) - One skill for the whole short-drama job: locked project settings, script checks, locked assets, storyboards and ready-to-paste video prompts.
- [OnlyShot Short Drama](https://github.com/A-cat-with-carrots/OnlyShot/tree/HEAD/SKILL.md) - Runs a whole short drama from one idea: market scan, story, script, storyboard images, then video through the Jimeng (Dreamina) CLI. Uses paid credits.

## Guides and prompts

- [Model guides](https://openmicrodrama.com/models) - Seedance, Kling, Veo, Hailuo and Wan for 9:16 drama: versions, prices, what works.
- [Prompt library](https://openmicrodrama.com/prompts) - 200 original prompts by model, genre and shot type (CC BY 4.0).
- [Script templates](https://openmicrodrama.com/scripts) - Ten micro-drama templates with beat sheets and a sample episode 1.
- [How to make an AI micro drama](https://openmicrodrama.com/guides/how-to-make-an-ai-micro-drama) - The whole pipeline, start to finish.
- [Cost breakdown](https://openmicrodrama.com/guides/cost-breakdown) - What a finished minute costs on each model.

## Contributing

Know a project that belongs here? [Submit it on OpenMicroDrama](https://openmicrodrama.com/submit) or open a pull request. It should be built for AI drama or AI video storytelling, updated in the last 90 days, and have install docs. This README is generated from the site's data, so a PR may be folded into the next regeneration rather than merged as is.

## License

The list text is [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Each project keeps its own license.
