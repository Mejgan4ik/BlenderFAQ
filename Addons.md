# Аддоны Blender / Blender Add-ons. Введение
## Что это? 
Аддоны это дополнительные программы, написанные сторонними разработчиками (а иногда и основыми), использующие внутренние API основной программы и расширяющие ее возможности. 

## Я не смогу без них работать в Blender?
Нет, сможете, но их использование обычно расширяет возможности и упрощает работу, автоматизирует рутинные операции. 

## Где найти addon-ы?
- https://blenderartists.org
- https://blendermarket.com
- https://gumroad.com

## Классификация
Addon-ы делятся на два типа: встроенные и внешние. Встроенные поставляются сразу с Blender, но по-умолчанию обычно выключены.
Включить их очень просто: через Preferences - Add-ons. 
Внешние addon-ы надо сначала найи в интернете, потом скачать и установить. Внешние аддоны могут быть бесплатными и платными, также они могут поставляться под разными лицензиями.


## Как установить Addon?
Обычно автор прилагает к аддону инструкции, но вот что нужно делать, если их нет:
1. Скачайте файл с zip-архивом аддона. Если аддон находится на Гитхабе, то поищите справа ссылку на релизы, там обычно должны  быть уже готовые архивы. 
2. В Blender откройте меню настроек (Preferences - Add-ons) и нажмите Install (в верхней части меню). Далее выберите файл с архивом, дальше Blender все сделаем сам. 
3. Теперь аддон появится в общем списке и можно нажать галочку напротив него, чтобы его включить. 

## Как им управлять?
Настройки аддона находятся внутри меню Preferences - Addons. Настройки есть далеко не у всех аддонов. 
Кроме того, дополнительные, оперативные настройки (те, которые используются во время работы), обычно скрываются в боковой панели, которая выезжает справа по нажатию на кнопку n. Там есть несколько табов, настройки могут быть в любом из них, обычно это указывается в документации.  

## Как его удалить?
![Remove_addons](https://user-images.githubusercontent.com/48691922/148991639-d1af339d-cf0e-4772-9489-868e592e26d8.jpg)
- в Blender откройте меню настроек (Preferences - Add-ons).
- найдите в списке аддонов тот, который хотите удалить.
- раскройте окно аддона, нажав на стрелочку слева от названия аддона, и нажмите кнопку **Remove** 

## Совместимость
> **ВАЖНО:** Аддоны имеют такую важную особенность, как совместимость с версиями Blender! Это касается сторонних аддонов, т.е. аддонов, которые не входят в "коробку" с программой. Если вы перейдёте по ссылке для скачивания соответствующего аддона, то **обязательно ознакомьтесь с его описанием**. Как правило, одним из первых пунктов будет указано, с какими версиями Blender совместим этот аддон.
> Аддон может работать с версиями, не указанными в описании, но гарантировать стабильность и правильность его функционирования никто не сможет. Использование несовместимых аддонов может повлечь за собой сбои в работе программы и потерю данных!

# Список addon-ов по категориям. 
В каждой категории сначала идут встроенные (не отмечены никак). <br>
Потом бесплатные внешние: у них есть ссылка, а потом платные: у них тоже есть ссылка и они отмеченны символом **$**

## Блокинг (драфт)
- [WonderMesh](https://blendermarket.com/products/wonder-mesh) **$** &mdash; аддон, который позволяет создавать 3D-примитивы (плоскость, куб, окружность, сфера, цилиндр, конус, капсула, тор, резьба) с множеством настроек, которые &mdash; и это очень важно! &mdash; возможно менять даже после манипуляций с этими примитивами (все стандартные трансформации + работа с некоторыми модификаторами). Есть бесплатная версия на [Github](https://github.com/WiresoulStudio/W_Mesh_28x/releases).
- [Black Mesh](https://blendermarket.com/products/black-mesh) **$** &mdash; аддон для быстрого концептирования, определения базовых форм будущих моделей.
- [Simply Concept](https://blendermarket.com/products/simply-concept) **$** &mdash; аддон для быстрого концептирования, определения базовых форм будущих моделей.

## Моделирование 
- LoopTools - дополнительные операции с вершинами, ребрами и поверхностями: выравнивание, выстроение по кругу, по кривой, задание общего промежутка между вершинами и прочее
- BoolTools - быстрые булевы операции за счет автоматизации наложения модификатора Boolean.
- [Cut Copy Paste](https://moth3r.gumroad.com/l/paste) Этот аддон предоставляет расширенные функции копирования/вставки для 3D-объектов и элементов режима редактирования.
- [Face Cutter](https://blendermarket.com/products/face-cutter) **$** &mdash; это удобный инструмент для моделирования, предназначенный для простой резки ngon`ов
- [MACHIN3tools](https://machin3.gumroad.com/l/MACHIN3tools) &mdash; это бесплатная постоянно развивающаяся коллекция инструментов блендера и круговых меню в одном настраиваемом пакете.
- [Ice Tools Pro](https://blendermarket.com/products/ice-tools-pro) **$** &mdash; Ice Tools Pro — это инструмент для моделирования на основе булевых операций и рисования, предназначенный для помощи в процессе моделирования твердых поверхностей и моделировании посредством ретопологии интуитивно понятным и ненавязчивым способом.
- [Blender Bezier Utils](https://github.com/Shriinivas/blenderbezierutils) &mdash; аддон значительно упрощающий работу с кривыми в Blender. При установке добавляет в панель инструментов (Т-панель) 2 кнопки, которые позволяют создавать и редактировать кривые. Подробнее об этом аддоне можно узнать из [плейлиста](https://www.youtube.com/playlist?list=PLxsh4i5F_h9G6QFoPzKvBRMayz8533fSW).
- [NGon Loop Select](https://amanbairwal.gumroad.com/l/NGonLoopSelect) &mdash; Позволяет выделять лупы с n-гонами.
- [JRemesh Tools](https://blendermarket.com/products/jremesh-tools)**$** &mdash; аддон позволяет преобразовать существующую сетку мэша в топологию на основе квадратов. Лучше всего подходит для твердотельного моделирования ([демо](https://www.youtube.com/watch?v=_HqngZdY1Ww)).
- [JCurve Tools](https://blendermarket.com/products/jcurve-tools)**$** &mdash; аддон позволяет создавать кривые на поверхности геометрии и не только. ([демо-1](https://youtu.be/6zGp4DCQ-JY)), ([демо-2](https://youtu.be/ZEhxaE3qik0)).
- [Grease Pencil From Mesh](https://blendermarket.com/products/grease-pencil-from-mesh)**$** &mdash; для преобразования обычных объектов в объекты Grease Pencil с фильтрацией краев для острых краев, пересечений и контуров изогнутых поверхностей ([демо](https://youtu.be/dyY8uGgTcEg)).
- [Cross Section Maker](https://blendermarket.com/products/cross-sections)**$** &mdash; это дополнение разработано для создания поперечного сечения из сетки ([демо](https://youtu.be/5VmeH15c378)).
- [Hole Maker](https://blendermarket.com/products/hole-maker)**$** &mdash; это дополнение представляет собой инструмент для создания отверстий в сетке с точным диаметром, глубиной и положением. Выбранная вершина - это центр отверстия ([демо](https://youtu.be/IxIsh0UowB0)).
- [Grid breaker](https://github.com/sorecords/gridbreaker) &mdash; для создания сетчатых сеток с управляемыми рандомизированными параметрами ([демо](https://youtu.be/hsaV0nBaSCk)).
- [Imagepaste](https://blendermarket.com/products/imagepaste)**$** &mdash; позволяет вставлять изображения из буфера обмена в различные места в Blender и легко копировать изображения обратно из Blender в буфер обмена ([демо](https://youtu.be/I58e2FRHJXA)).
- [Cablerator](https://kritskiy.gumroad.com/l/cblrtr)**$** &mdash; Создает кабели между точками без возни с кривыми. Можно рисовать по поверхности и создать результирующий кабель, можно просто указать две точки в пространстве и между ними будет проложен кабель. 

## Работа с нодами
- [NodeRelax](https://github.com/Shahzod114/NodeRelax-Blender-Addon) &mdash; Расслабляющая кисть для нодов, помогает легче расположить нодв. Хоткей: Shift+R

## Текстурирование 
- [Bpainter](https://blendermarket.com/products/bpainter) **$** &mdash;  мощный аддон для текстурирования а-ля Substance Painter прямо в Blender 

## Риг
- Rigify &mdash; создает автоматические риги и контролы для двухногих и четырехногих существ. Перед использованием посмотрите уроки по нему, или прочтите документацию, нужно осознать принципы его работы.
- [WiggleBones](https://blenderartists.org/t/wiggle-bones-a-jiggle-bone-implementation-for-2-8/1154726) 
- [X-Muscle System](https://blendermarket.com/products/x-muscle-system) **$**
- [AutoRig PRO](https://blendermarket.com/products/auto-rig-pro) **$**

## Анимация

## Физика
- [Physics Dropper](https://blendermarket.com/products/physics-dropper)**$** &mdash; c помощью этого аддона вы можете "уронить" выбранные объекты на любые другие объекты всего один хоткеем.

## Работа с HardSurface
- Carver &mdash; Бесплатный аналог BoxCutter. Позволяет визуально вырезать объемы из моделей. Итогом работы будет исходная модель и множество вырезающих мешей, в комплекте с настроенными boolean модификаторами. Таким образом, моделирование происходит в неразрушающем режиме. 
- [MeshMachine](https://blendermarket.com/products/meshmachine) **$**
- [DecalMachine](https://blendermarket.com/products/decalmachine) **$** 
- [HardOPS](https://blendermarket.com/products/hardopsofficial) **$**
- [BoxCutter](https://blendermarket.com/products/boxcutter) **$**
- [Destructive extrude](https://github.com/Darcvizer/Destructive-Extrude) &mdash; аддон, доводящий до ума встроенный инструмент Блендера Extrude Manifold. Инструмент экструдирования, основанный на Булевых операциях. Аддон относится к экспериментальным, находится в бете, так что возможны непредсказуемые результаты.

## Работа со Sculpt
- [MeshFairing](https://github.com/fedackb/mesh-fairing) 
- [Sculpt Alphas Manager](https://github.com/Ryxx/Sculpt-Alphas-Manager) &mdash; менеджер альфа-изображений для скульпта. [Видео](https://www.youtube.com/watch?v=wHR8baLhnoA&ab_channel=StevenScott
) с пояснениями.
- [Brush manager](https://tingjoybits.gumroad.com/l/zLBPz) &mdash; менеджер кистей для скульпта. Цена начинается от 0$, но можно и заплатить, сколько пожелаете. 
- [Blender Sculpt Layers](https://mifth.gumroad.com/l/blender_sculpt_layers) **$** &mdash; У Blender пока нет нативных слоев для скульпта, но этот аддон их добавляет. 
- [Extended Sculpt Tools](https://biman.gumroad.com/l/dUbp) **$** 
- [SpeedSculpt](https://blendermarket.com/products/speedsculpt) **$** 
- [Paint Wheel](https://jfranmatheu.gumroad.com/l/blender_sculpt_paint_wheel) **$**  &mdash; Круговое меню а-ля Zbrush с кистями и цветами

## Ретопология
- Bsurface &mdash; построение топологии поверх других объектов с помощью annotate tool - то есть вы просто рисуете на поверхности линии и они превращаются в геометрию! 
- F2 &mdash; кнопка F на стероидах. Позволяет строить поверхности волшебным образом по двум ребрам или по трем точкам. Очень удобен для ретопологии.
- [MiraTools](https://blenderartists.org/t/miratools/637385) &mdash; многофункциональный аддон, применяется не только для ретопологии.
- [PolyQuilt](https://github.com/sakana3/PolyQuilt) &mdash; Прекрасный и недооцененный аддон, есть несколько вариантов построения геометрии, а также есть функция разглаживания. Работает полностью в Edit mode, никаких проблем с производительностью нет. Очень гибко настраивается и настройки можно сохранить. Повторяет рабочий процесс и принципы ретопологии в Maya. 
- [Retopo MT](https://cwolf3d.gumroad.com/l/cNGNb) &mdash; полнофукнциональный аддон для ретопологии: можно рисовать полигонные линии, как в Bsurface, легко строить геометрию вокруг цилинидрических форм, также позволяет легко удалять геометрию. 
- [Draw X-Ray](https://bartoszstyperek.gumroad.com/l/draw_xray) **$** &mdash; (есть и бесплатная версия с меньшим фукнционалом). Устраняет одну из проблем  ретопологии в Blender - правильно отображает сетку поверх другого объекта. 
- [SpeedRetopo](https://pitiwazou-1.gumroad.com/l/speedretopo) **$** &mdash; интегрирующий аддон для других аддонов и функций Blender для ускорения процесса ретопологии, ничего нового не вносит, просто собирает все в одно удобное боковое или pie-меню. 
- [Retopoflow 3](https://blendermarket.com/products/retopoflow) **$** &mdash; есть бесплатная версия на [Github](https://github.com/CGCookie/retopoflow). Один из самых продвинутых аддонов ретопологии для Blender. Обладает рядом инструментов для современной ретопологии и даже свой собственный пользовательский интерфейс. К недостаткам стоит отнести медленную работу, особенно на тяжелых и сложных моделях. 
- [Tesselator - Quadrilateral Remeshing](https://blendermarket.com/products/tesselator) **$** &mdash; это аддон для ретопологии, который поможет вам легко создавать обычные четырехугольные и треугольные сетки из скульптов.
- [Softwrap](https://www.blendermarket.com/products/softwrap) **$** &mdash; интересный аддон с совершенно особенным подходом: с его помощью натягивается уже готовая лоуполи болванка поверх хайполи скульта. 
- [Petik](https://blendermarket.com/products/petik)**$** &mdash; это простой инструмент для ретопологии. Он позволяет вам определять ваши собственные геометрические патчи именно так, как они вам нужны. Вы получаете до шести сторон одного участка и переменное количество вершин на каждой стороне. ([демо](https://lh5.googleusercontent.com/yO61N9hw1D9netLGo-Y7Q9rEZfngi4wQIgFsVXL5jyPLDfRGyy8jepPcz6Xh5ZlSxecvX3NDvWATk3SSCCXqGWOtBK-g7TzBcefJmUQrTWk3LEDKuVMyzHl3iAhx_oxi-9KSaK9Q)).
- [Quad Remesher](https://exoside.com/quadremesher/)**$** &mdash; это дополнение  ([демо](https://youtu.be/6BvP3rXeRRI)).

## Интерфейс
- [Screencast Keys](https://github.com/nutti/Screencast-Keys) &mdash; показывает нажатия кнопок на клавиатуре, а также действия с мышью
- [Simple Tabs](https://blendermarket.com/products/simple-tabs)**$** &mdash; помогает организовать вашу N-панель ([демо](https://youtu.be/6h3SyW0YgRs)).

## Геоданные
- [blender-osm](https://prochitecture.gumroad.com/l/blender-osm) &mdash; загрузка данных из OpenStreetMap
- [Maps Models Importer](https://github.com/eliemichel/MapsModelsImporter) &mdash; загрузка данных из Google Maps

## Rendering 
- [LuxCore Render](https://github.com/LuxCoreRender/BlendLuxCore/releases) 
- Поддержка движка Appleseed в аддоне [Blenderseed](https://github.com/appleseedhq/blenderseed)
- [Colorframe Renders Pro](https://blendermarket.com/products/petik)**$** &mdash; аддон, который поможет создать разноцветный WireFrame рендер. ([демо](https://youtu.be/rS6cCK9Qfz0)).

## Волосы и шерсть
- [Hair Tool](https://bartoszstyperek.gumroad.com/l/hairtool) **$**

## Импорт / экспорт
- FBX import/export &mdash; must have аддон, позволяет экспортировать/импортировать FBX формат - стандартный в индустрии формат для обмена данными между 3D-программами. На данный момент осуществляется поддержка только бинарного формата.
- COLLADA DAE import/export &mdash; формат обмена данными между 3D-программами. Является текстовым, XML-совместимым.
- USD import/export &mdash; формат обмена данными между 3D-программами, созданный Pixar. Может быть как текстовым, так и бинарным (usdc и usdz).
- SVG import/export &mdash; импорт/экспорт векторной графики в открытом формате SVG. Поддерживается практически всем графическим ПО.
- STL import/export &mdash; работа с форматом STL - еще один формат обмена данными между 3D-программами. В основном используется в чертежных программах, а также в технологиях 3D-печати. Может быть как текстовым, так и бинарным.
- OBJ import/export &mdash; формат 3D-объектов от Wavefront. До появления FBX был основным форматом обмена данными. Не поддерживает анимации и разделение пивотов объектов (пивот всегда будет в центре экспортируемой сцены). Является текстовым форматом.
- glTF &mdash; новый, прогрессивный формат хранения 3D-сцен и моделей. Основан на JSON. Есть поддержка бинарной версии (формат glb). Поддерживает информацию о сцене: камеры и источники света, скелетную анимацию, материалы и шейдеры.
- [SCS Blender Tools](https://github.com/SCSSoftware/BlenderTools) &mdash; инструменты для редактирования ассетов в играх от SCS Software
- [Unreal Blender Tools](https://epicgames.github.io/BlenderTools/) &mdash; средства для работы с Unreal Engine 4
- [Blender 3ds Importer (Recoverd Vesion)](https://blendermarket.com/products/blender-3ds-importer-addon-recoverd-vesion)**$** &mdash; аддон позволяет импортировать 3DS модели в ваш проект.

## Природные явления и живая природа
- Sapling tree generator &mdash; генератор деревьев
- Real Snow &mdash; делает снег, почти как настоящий
- IvyGen -&mdash;генгератор листвы 
- A.N.T. Landscapes &mdash; создание процедурных гор
- Sun Position &mdash; располагает и анимирует источник света в соответствии с реальным положением cолнца.  Использует географическую позицию, время и дату
- Dynamic Sky &mdash;создает процедурное небо и солнце. Можно создать сцену на открытом воздухе или в помещении с разными настройками освещения. 
- [Graswald](https://blendermarket.com/products/graswald) **$** &mdash; мощный аддон для генерации травы и листьев.
- [The Grove](https://www.thegrove3d.com/) **$** &mdash; еще один мощный аддон для гегнерации деревьев и кустов.

## Архитектура
- Archimesh
- Archipack

## Ускорение работы и дополнительные инструменты
- Node Wrangler &mdash; ускорение работы с нодами в shader editor и композере, может добавлять типичные связки нод одним кликом, объединять ноды, удалять ненужные и многое другое. 
- MeasureIT &mdash; аддон, который позволяет производить измерения. 
- Stored Views &mdash; сохраняйте и восстанавливайте пользовательские виды, точку зрения и расположение камер.
- BoltFactory &mdash; настоящая фабрика болтов и гаек.
- Extra Objects &mdash; аддон, позволяющий создавать дополнительные примитивные и не только примитивные объекты.
- tinyCAD &mdash; добавляет некоторые CAD функции в Blender.
- [Pie menu editor](https://blendermarket.com/products/pie-menu-editor) **$** &mdash; создание своих собственных круговых меню.
- [3 Points Align](https://blendermarket.com/products/3-points-align) **$** &mdash; с помощью этого аддона вы можете легко выровнять и привязать один объект к другому, рисуя линии от целевой сетки к исходной ([демо](https://www.youtube.com/watch?v=WohYWCApftI)).
- [Mesh Align Plus](https://github.com/egtwobits/mesh_mesh_align_plus/releases) &mdash; мощный аддон для выравнивания объектов (имеет множество натсроек и параметров, по которым производится выравниевание) ([демо](https://blenderartists.org/uploads/default/original/4X/2/2/6/2263f2d1146dbe9ae922e092340996e9fa13db35.gif)),([демо](https://blenderartists.org/uploads/default/original/4X/6/9/3/693354de8c55126ce11a8c45a087f7b2de48f525.gif)).
- [3 Points Align](https://blendermarket.com/products/3-points-align)**$** &mdash; это дополнение позволит легко выровнять и привязать один объект к другому, проведя линии от целевой сетки к исходной  ([демо](https://youtu.be/WohYWCApftI)).
- [Atomic Data Manager](https://remington.pro/software/blender/atomic/) &mdash; это многофункциональное дополнение предоставляет художникам все необходимые инструменты для удаления нежелательных и неиспользуемых данных из их файлов Blender ([демо](https://youtu.be/Wo68No4h-DA)).

## Работа с камерой
- Add camera rig
- [Real camera](https://3d-wolf.com/products/camera/) &mdash; позволяет управлять камерой Blender как настоящей (автоэкспозиция, автофокус)
- [Photographer 4](https://chafouin.gumroad.com/l/HPrCY) **$** &mdash; добавляет новую физическую камеру, настройки физического освещения и интерфейсы микшера для источников света, эмиссионных материалов и миров для EEVEE, Cycles и LuxCore 2.5 ([демо](https://www.youtube.com/watch?v=q_IzKyDD2KY)). Есть бесплатная версия [Photographer 2](https://chafouin.gumroad.com/l/FWQf), но она работает на версиях до 2.9.
- [Cinepack](https://blendermarket.com/products/cinepack-pre-animated-camera-moves) **$** &mdash; Предварительно анимированные движения камеры ([демо](https://youtu.be/tWnuaHjTGcM)).
- [Fspy](https://fspy.io/) &mdash; уже не аддон, а отдельная программа, но плотно работает с Blender: позволяет выставить камеру в Blender, в точности как она установлена на снимке. 

## Освещение
- [LeoMoon Light Studio](https://github.com/leomoon-studios/leomoon-lightstudio) &mdash; аддон, который позволяет настроить студийное освещение ([демо](https://www.youtube.com/watch?v=LyxA2Jgn5zQ)). Аддон имеет открытый код и является абсолютно бесплатным, но если вы посчитаете нужным отблагодарить автора, то можете приобрести его по этой [ссылке](https://blendermarket.com/products/leomoon-lightstudio).

## Работа с UV развёрткой
- Magic UV
- [TexTools](http://renderhjs.net/textools/blender/)
- [UV Packer](https://www.uv-packer.com/blender/) &mdash; это автоматизированное приложение для UV-упаковки одним щелчком мыши.
- [UV Squares](https://github.com/Radivarig/UvSquares) &mdash; инструмент для UV Editor в Blender, который преобразует выделеные шэлы UV в квадратную сетку.
- [Texel Density Checker](https://mrven.gumroad.com/l/CEIOR) &mdash; Рассчитать плотность текселей для модели с текстурой разного размера (512–4096 пикселей) или с нестандартным размером и соотношением сторон. Аддон бесплатный, но вы можете отблагодарить автора и купить его по той же ссылке.
- [Uv Packmaster 3](https://blendermarket.com/products/uvpackmaster) **$** &mdash; Один из самых эффективных упаковщиков UV ([UV Packmaster features](https://uvpackmaster.com/for-blender/features/)),([UV Packmaster FAQ](https://uvpackmaster.com/for-blender/uvpackmaster-3-faq/))
- [Zen UV](https://blendermarket.com/products/zen-uv) **$** &mdash; это не просто набор инструментов, это готовый конвейер для быстрого создания UV в Blender ([демо](https://youtu.be/Yj2SecY-c1Y))([документация](https://zen-masters.github.io/Zen-UV/)).

## "Мосты" - аддоны для обмена данными с другим софтом
- [Blender to Substance 3D Painter](https://github.com/DigiKrafting/blender_addon_substance_painter) &mdash; Мост который позволяет отправить модель(сцену, коллекцию) в Substance 3D Painter, а после текстурирования импортирует и применяет полученные текстурные карты на объекты внутри Blender.
> Для работы аддона требуется, чтобы в системе был установлен Adobe Substance 3D Painter.
- [Headus UVlayout Bridge](https://github.com/schroef/uvlayout_bridge) &mdash; аддон для экспорта объектов из Blender в Headus UVlayout и обратного импорта развёрнутого объекта. Имеет множество опций и возможностей автоматизации.
> Для работы аддона требуется, чтобы в системе был установлен Headus UVlayout.
- [HeadusUVLayout/RizomUV bridge (2 in 1)](https://titus.gumroad.com/l/B2RUVL) **$** &mdash; аддон для экспорта объектов из Blender в Headus UVlayout или RizomUV  и обратного импорта развёрнутого объекта. [(демо)](https://www.youtube.com/watch?v=XusjghptcWI)
> Для работы аддона требуется, чтобы в системе были установлены Headus UVlayout и RizomUV.

## Аддоны All in One (многофункциональные аддоны)
- [BagaPie](https://blenderartists.org/t/bagapie-modifier-free-addon/1310959) &mdash; это универсальный и бесплатный аддон, который создаёт пресеты из модификаторов и геометрических нод (Он в основном предназначен для архитектуры) ([демо](https://youtu.be/nDeK29aAUps)),([документация](https://www.f12studio.fr/bagapie)). Аддон бесплатный, но вы можете отблагодарить автора и купить его.

## Работа с графами (Graph Editor)
- [Graphkit](https://blendermarket.com/products/graphkit) **$** &mdash; дополнение Graphkit от Blastframe - незаменимый инструмент для анимации в Blender! Благодаря 6 мощным функциям, которые экономят вам массу шагов, он гарантированно станет неотъемлемой частью вашего рабочего процесса анимации [(демо)](https://youtu.be/59vDUmzThII)

## Работа с файлами
- [Power Save](https://bonjorno7.gumroad.com/l/powersave) &mdash; это инструмент, предназначенный для упрощения сохранения (автосохранения) и повышения доступности сохранённых файлов. [(демо)](https://youtu.be/8C-N4BZjesA)
