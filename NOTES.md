# Заметки к гайду (14.11.2026)

## Убрано из прошлой версии (30 → отбор заново)
| Скилл | Почему убран |
|---|---|
| zenstory-ai/drama-skills/short-drama-storyboard | раскадровка живых сериалов-дорам, не мульт |
| 101-skills/superpowers/seedance | общий генератор видео Seedance 2.0 |
| hexiaochun/seedance2-api/seedance2-api | общий конвейер Seedream → Seedance, не про мульт |
| openmontageinc/openmontage/kling-official | общий генератор видео Kling |
| prime-skills/runcomfy-agent-skills/lipsync | общий lip-sync живых лиц и аватаров |
| nexu-io/open-design/fal-lip-sync | говорящие головы / аватары, общий lip-sync |
| roble3/cc-blender-skill/animation-quality-gate | проверка моушн-дизайна в Blender (морфинг, слои), не персонажей |
| gamedev-skills/.../unity-animation, godot-animation | игровой движок: подключение анимаций в коде игры, а не создание мульта |
| quodsoler/unreal-engine-skills/ue-animation-system | то же, Unreal Engine |
| el4cteo/roblox-skills/roblox-characters-animation | то же, Roblox |

## Добавлено
cth9191/animate, 0x0funky/agent-sprite-forge/generate2dsprite, nilbuild/page-mascot, 101-skills/superpowers/character-design-sheet,
scenario-labs: grease-pencil, storyboards, maya-animation; el4cteo/blender-skills/blender-facial-shapekeys;
arjun988/blender-skills: cartoon-style, anime-style, stop-motion-craft-style.

## Рассмотрено и не взято
- openfilm/openfilm, seedance-prompt-en, ltx2, fal-kling-o3, openmontage seedance-2-0, higgsfield-* — общие генераторы видео.
- eternityspring/novel-storyboard — раскадровка ИИ-дорам (живое кино).
- jimliu/baoyu-comic, zsyggg/paper-comic — комиксы, не анимация.
- scenario-blender-2d-animation — параллакс-шоты для игровых трейлеров (ближе к моушну).
- nexu-io/open-design/sprite-animation — анимированный слайд-объяснялка (моушн-дизайн).
- heygen hyperframes*, emilkowalski/*, gsap, lottie, framer-motion, manim, whiteboard/explainer (iart-ai) — UI-анимация и моушн-дизайн.
- delphi-ai/animate, niazmorshed2007/reanimate — анимация интерфейсов сайта.
- agents365-ai/bangumi-frames — вытаскивает кадры из аниме, не делает анимацию.
- mengto/build-rigged-game-assets — пайплайн игровых ассетов.
- scenario-blender-previs-storyboard, scenario-maya-rigging, el4cteo blender-animation / blender-character-rigging — дубли, не влезли в лимит 30.
- calesthio 2d-character-rig-animation (344 уст., 243 зв.), dylantarre character-appeal (673 уст., 156 зв.) — ниже порога.

## Картинки: где искали и что отбросили
Проверено для каждого скилла: README репозитория, все картинки в репо (assets/docs/examples/src/tests), релизы (GitHub API),
сайт проекта (spritecook.ai, layer.ai, scenario.com, openmontage.video, blender-skills.vercel.app, koboyo.com/page-mascot),
вложения в issues/PR (GitHub search API).
- cartoon-3d-short: прошлые картинки удалены — папка references это кадры чужого канала, автор: «for style study only».
- roble3: в репо есть только вращающийся куб (turntable), не персонаж — не взят.
- openmontage: ролики в README сделаны Kling/Veo, а не этими скиллами — не взяты.
- layer.ai: галерея сайта — работы пользователей, не примеры скиллов — не взята.
- scenario-labs: картинки в tests/ только для Roblox-скиллов — не взяты.
- el4cteo: ходьба солдата — пример всего проекта, подписано в гайде; MP4 конвертирован в GIF (480 px, 12 fps).
- SpriteCook: лист кадров с сайта сервиса, подписано.

## Источники картинок
- out/img/01-3d-animation-short-generator-1.gif ← https://github.com/minimax-ai/minimax-h3/blob/HEAD/assets/3d-animation-short-generator.gif
- out/img/02-papercraft-stop-motion-explainer-1.gif ← https://github.com/minimax-ai/minimax-h3/blob/HEAD/assets/papercraft-stop-motion-explainer.gif
- out/img/03-animate-1.jpg ← https://github.com/cth9191/animate/blob/HEAD/docs/styles.png
- out/img/03-animate-2.jpg ← https://github.com/cth9191/animate/blob/HEAD/docs/storyboard.png
- out/img/04-anidoodle-1.jpg ← https://github.com/alexgreensh/anidoodle/blob/HEAD/assets/styles.jpg
- out/img/04-anidoodle-2.gif ← https://github.com/alexgreensh/anidoodle/blob/HEAD/assets/act1.gif
- out/img/05-page-mascot-1.jpg ← https://github.com/nilbuild/page-mascot/blob/HEAD/.github/sheets.png
- out/img/05-page-mascot-2.jpg ← https://github.com/nilbuild/page-mascot/blob/HEAD/.github/styles.png
- out/img/06-spritecook-animate-assets-1.png ← https://www.spritecook.ai/assets/examples/pixel-art-characters/royal-goblin/idle_sheet.png
- out/img/07-blender-facial-shapekeys-1.gif ← https://github.com/el4cteo/blender-skills/blob/HEAD/docs/comparison/media/soldier-skill.mp4
- out/img/08-generate2dsprite-1.gif ← https://github.com/0x0funky/agent-sprite-forge/blob/HEAD/src/v040/aria-set.gif
- out/img/08-generate2dsprite-2.gif ← https://github.com/0x0funky/agent-sprite-forge/blob/HEAD/src/v040/aria-in-scene.gif

## Правка 14.11 (по ревью Jessica)
- blender-facial-shapekeys перенесён в «Без примеров»: GIF солдата не показывает мимику.
- Внутри групп сначала скиллы, проходящие по своим установкам (>1000), потом по звёздам.
