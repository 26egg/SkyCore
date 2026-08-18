# SkyCore

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Paper](https://img.shields.io/badge/Paper-1.21%2B-brightgreen)
![Java](https://img.shields.io/badge/Java-21-orange)
![Vault](https://img.shields.io/badge/Vault-Supported-purple)

SkyCore هو بلوقن مخصص لماينكرافت يضيف نظام **Weapon Cores** و **Armor Cores** بإحصائيات عشوائية، مع نظام **Blacksmith** لاستبدال الـCore الموجود على الأسلحة والدروع.

تم تصميم البلوقن ليكون مناسبًا لسيرفرات **RPG وSkyblock وSurvival** التي تعتمد على التقدم، الندرات، تطوير المعدات، الـBosses والـRewards.

---

# المميزات الرئيسية

- Weapon Cores للأسلحة
- Armor Cores للدروع
- إحصائيات عشوائية لكل Core
- أربع درجات Rarity
- Custom Player Head Textures
- Weapon Attributes حقيقية
- Critical Hit System
- Life Steal
- Defense
- Fire Resistance
- Poison Resistance
- Max Health
- نظام Blacksmith كامل
- دعم Vault Economy
- GUI قابل للتعديل
- Sounds قابلة للتعديل
- Messages قابلة للتعديل
- أسعار مختلفة حسب Rarity
- دعم Console Commands
- إعطاء أكثر من Core بأمر واحد
- مناسب للربط مع MythicMobs
- Configurable Stats
- Configurable Textures

---

# Weapon Cores

Weapon Core مخصص لتطوير الأسلحة.

يمكن تركيبه على:

- Swords
- Axes

كل Weapon Core يحصل على مجموعة إحصائيات عشوائية حسب الـRarity الخاصة به.

## Weapon Stats

| Stat | الوظيفة |
|---|---|
| Attack Damage | زيادة الضرر الأساسي للسلاح |
| Attack Speed | زيادة سرعة الهجوم |
| Critical Rate | نسبة حدوث Critical Hit |
| Critical Damage | زيادة قوة الضربة الحرجة |
| Life Steal | استرجاع جزء من الصحة عند ضرب الخصم |

## Weapon Core داخل اللعبة

<img src="./assets/weapon-core.png" alt="Weapon Core" width="500">

---

# Armor Cores

Armor Core مخصص لتطوير قطع الدروع.

يمكن تركيبه على:

- Helmet
- Chestplate
- Leggings
- Boots

كل Armor Core يحصل على Stats عشوائية حسب الـRarity الخاصة به.

## Armor Stats

| Stat | الوظيفة |
|---|---|
| Defense | تقليل الضرر الجسدي |
| Max Health | زيادة الحد الأقصى للصحة |
| Fire Resistance | تقليل ضرر النار واللافا |
| Poison Resistance | تقليل ضرر السم |

> **ملاحظة:**  
> Fire Resistance وPoison Resistance لا يمكن أن يظهرا معًا داخل نفس Armor Core.

## Armor Core داخل اللعبة

<img src="./assets/armor-core.png" alt="Armor Core" width="500">

---

# Rarities

SkyCore يحتوي حاليًا على أربع درجات:

| Rarity | المستوى |
|---|---|
| Common | البداية |
| Epic | متوسط |
| Legendary | قوي |
| Special | الأعلى |

كلما ارتفعت الـRarity:

- ترتفع قوة الإحصائيات
- يزيد عدد الإحصائيات الممكنة
- يصبح الـCore أكثر قيمة
- تزداد تكلفة استبداله في Blacksmith

---

# Core Statistics

عند تركيب Core على سلاح أو درع، يتم نقل الإحصائيات إلى القطعة نفسها.

مثال:

```text
✦ Core Statistics
Attack Damage: +6.9
Critical Rate: +7.2%

⚔ Weapon Statistics
Damage: 14.9
Attack Speed: 1.6

Core: LEGENDARY
