# SkyCore

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Paper](https://img.shields.io/badge/Paper-1.21%2B-brightgreen)
![Java](https://img.shields.io/badge/Java-21-orange)
![Vault](https://img.shields.io/badge/Vault-Supported-purple)
المميزات الرئيسية

Weapon Cores مخصصة للأسلحة

Armor Cores مخصصة للدروع

إحصائيات عشوائية لكل Core

أربع درجات Rarity مختلفة

Custom Player Head Textures

Weapon Attributes حقيقية

Critical Hit System

Life Steal

Defense

Fire Resistance

Poison Resistance

Max Health

نظام Blacksmith متكامل

دعم Vault Economy

GUI قابل للتعديل

Messages وSounds قابلة للتعديل

أسعار مختلفة حسب الـRarity

دعم أوامر الـConsole

إمكانية إعطاء أكثر من Core بأمر واحد

مناسب للربط مع MythicMobs والـCrates والـBoss Rewards

Stats وTextures قابلة للتعديل من ملفات الإعدادات

Weapon Cores

الـWeapon Core مخصص لتطوير الأسلحة، ويمكن تركيبه على:

Swords

Axes

يحصل كل Weapon Core على مجموعة من الإحصائيات العشوائية بناءً على الـRarity الخاصة به.

Weapon Stats

Stat

الوظيفة

Attack Damage

زيادة الضرر الأساسي للسلاح

Attack Speed

زيادة سرعة الهجوم

Critical Rate

نسبة حدوث Critical Hit

Critical Damage

زيادة قوة الضربة الحرجة

Life Steal

استرجاع جزء من الصحة عند إلحاق الضرر بالخصم

Weapon Core داخل اللعبة

<p align="center">
  <img src="./assets/weapon-core.png" alt="SkyCore Weapon Core" width="600">
</p>

Armor Cores

الـArmor Core مخصص لتطوير قطع الدروع، ويمكن تركيبه على:

Helmet

Chestplate

Leggings

Boots

يحصل كل Armor Core على مجموعة من الإحصائيات العشوائية بناءً على الـRarity الخاصة به.

Armor Stats

Stat

الوظيفة

Defense

تقليل الضرر الجسدي المستلم

Max Health

زيادة الحد الأقصى لصحة اللاعب

Fire Resistance

تقليل الضرر الناتج عن النار واللافا

Poison Resistance

تقليل الضرر الناتج عن السم

ملاحظة: لا يمكن أن يظهر Fire Resistance وPoison Resistance معًا داخل Armor Core واحد.

Armor Core داخل اللعبة

<p align="center">
  <img src="./assets/armor-core.png" alt="SkyCore Armor Core" width="600">
</p>

Rarities

يحتوي SkyCore حاليًا على أربع درجات من الندرة:

Rarity

المستوى

Common

البداية

Epic

متوسط

Legendary

قوي

Special

الأعلى

كلما ارتفعت الـRarity:

ترتفع قوة الإحصائيات

يزيد عدد الإحصائيات الممكنة

يصبح الـCore أكثر قيمة

تزداد تكلفة تركيبه أو استبداله في الـBlacksmith

Core Statistics

عند تركيب Core على سلاح أو قطعة درع، تُنقل إحصائياته إلى القطعة نفسها وتظهر داخل الـLore بشكل منظم وواضح.

مثال على سلاح يحمل Weapon Core:

✦ Core Statistics
Attack Damage: +6.9
Critical Rate: +7.2%

⚔ Weapon Statistics
Damage: 14.9
Attack Speed: 1.6

Core: LEGENDARY

إحصائيات السلاح بعد تركيب الـCore

<p align="center">
  <img src="./assets/weapon-stats.png" alt="SkyCore Weapon Statistics" width="600">
</p>

Blacksmith

يتيح نظام Blacksmith للاعب تركيب Core على سلاح أو قطعة درع، كما يسمح باستبدال الـCore الحالي بواحد جديد مقابل تكلفة مالية تعتمد على الـRarity.

طريقة الاستخدام:

ضع السلاح أو قطعة الدرع في الخانة المخصصة.

ضع الـCore المتوافق في خانة الـCore.

راجع السعر والمعلومات الظاهرة داخل الـGUI.

أكّد العملية لتركيب الـCore الجديد.

عند استبدال Core موجود، تتم إزالة إحصائيات الـCore القديم وتطبيق إحصائيات الـCore الجديد، لمنع تراكم الإحصائيات على القطعة نفسها.

واجهة الـBlacksmith

<p align="center">
  <img src="./assets/blacksmith.png" alt="SkyCore Blacksmith GUI" width="700">
</p>

الاقتصاد

يدعم SkyCore نظام Vault Economy لحساب تكلفة تركيب واستبدال الـCores. ويمكن تحديد سعر مختلف لكل Rarity من ملفات الإعدادات.

يتطلب استخدام النظام الاقتصادي وجود:

Vault

بلوقن Economy متوافق مع Vault

التخصيص

يمكن تعديل الأنظمة الأساسية للبلوقن من ملفات الإعدادات، بما في ذلك:

نطاقات الـStats لكل Rarity

أسعار الـBlacksmith

Player Head Textures الخاصة بالـCores

أسماء العناصر والـLore

رسائل البلوقن

الأصوات

عناصر وتصميم الـGUI

التوافق

Server Software: Paper 1.21+

Java: Java 21

Economy: Vault

مناسب للاستخدام مع MythicMobs والـCrates وأنظمة الـBoss Rewards

التثبيت

تأكد من تشغيل السيرفر على Java 21 وPaper 1.21+.

ثبّت Vault وبلوقن Economy متوافقًا معه إذا كنت تريد استخدام نظام الأسعار.

ضع ملف SkyCore.jar داخل مجلد plugins.

أعد تشغيل السيرفر.

عدّل ملفات الإعدادات التي ينشئها البلوقن بما يناسب نظام سيرفرك.

فكرة الاستخدام

يمكن منح الـCores للاعبين من خلال:

Boss Drops

MythicMobs

Crates

Quests

Events

Daily Rewards

متجر السيرفر

بهذا يصبح تطوير الأسلحة والدروع جزءًا أساسيًا من تقدم اللاعب، بدل الاعتماد على المعدات العادية فقط.

ملاحظات مهمة

يجب أن يكون نوع الـCore متوافقًا مع نوع القطعة المستخدمة.

الـWeapon Cores تعمل على السيوف والفؤوس فقط.

الـArmor Cores تعمل على قطع الدروع فقط.

استبدال الـCore لا يكدّس الإحصائيات القديمة مع الجديدة.

جميع القيم والأسعار والرسائل والأصوات قابلة للتخصيص.

SkyCore

نظام تطوير معدات مصمم لإضافة تقدم أعمق، ندرة حقيقية، وقيمة أكبر للـBosses والـRewards داخل سيرفرك.
