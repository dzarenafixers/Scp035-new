# SCP035Plugin eng

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Overview

`SCP035Plugin` is a plugin for SCP: Secret Laboratory that uses the EXILED framework to add a custom item called "SCP-035 Mask". This item allows players to transform into SCP-035 upon use.

## Features

- **Custom Item**: SCP-035 Mask
  - Allows players to transform into SCP-035 for 30 seconds.
  - Applies a visual mask effect to the player upon transformation.
- **Control Transformation Duration**: The duration of the transformation can be configured.
- **Specific Spawn Points**: The item can spawn in specific locker points within the game.

## Requirements

- **EXILED Framework**: Ensure EXILED is installed on your SCP: Secret Laboratory server.
- **Game Version**: Compatible with the game version specified in `RequiredExiledVersion` in the code.

## Installation

1. **Download EXILED**:
   - Download and install EXILED from the [EXILED GitHub page](https://github.com/galaxy119/EXILED).

2. **Download the Plugin**:
   - Download the DLL file of the plugin and place it in the `Plugins` folder of your SCP: Secret Laboratory server.

3. **Configure the Plugin**:
   - Edit the EXILED configuration file to configure the plugin and specify the custom item ID. You can use the example below:

   ```yaml
   SCP035Plugin:
     IsEnabled: true
     SCP035MaskId: 51
   # ________________________________________________________________
   # SCP035Plugin ar

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## نظرة عامة

`SCP035Plugin` هو بلجن للعبة SCP: Secret Laboratory يستخدم إطار عمل EXILED لإضافة عنصر مخصص جديد يسمى "SCP-035 Mask". يسمح هذا العنصر للاعبين بالتحول إلى SCP-035 عند استخدامه.

## الميزات

- **عنصر مخصص**: SCP-035 Mask
  - يتيح للاعبين التحول إلى SCP-035 لمدة 30 ثانية.
  - يتم تطبيق تأثير مرئي للقناع على اللاعب عند التحول.
- **تحكم في مدة التحول**: يمكن تعديل مدة التحول من خلال إعدادات البلجن.
- **نقاط ظهور محددة**: يمكن للعنصر أن يظهر في نقاط ظهور محددة في اللعبة.

## المتطلبات

- **إطار عمل EXILED**: يجب تثبيت EXILED على خادم SCP: Secret Laboratory الخاص بك.
- **نسخة اللعبة**: متوافقة مع نسخة اللعبة التي تم تحديدها في `RequiredExiledVersion` في الكود.

## التثبيت

1. **تنزيل EXILED**:
   - قم بتنزيل وتثبيت EXILED من [صفحة GitHub الخاصة بـ EXILED](https://github.com/galaxy119/EXILED).

2. **تنزيل البلجن**:
   - قم بتنزيل ملف DLL للبلجن وضعه في مجلد البلجنات الخاص بخادم SCP: Secret Laboratory الخاص بك.

3. **إعداد التكوين**:
   - قم بتعديل ملف التكوين الخاص بـ EXILED لإعداد البلجن وتحديد معرف العنصر المخصص. يمكنك استخدام المثال التالي:

   ```yaml
   SCP035Plugin:
     IsEnabled: true
     SCP035MaskId: 51
