# Reception Robot – IoT Chat Interface

This is a simple reception robot control and chat system built using HTML/CSS for the UI, PHP for backend control logic, and IBM Watson Assistant for Arabic-language chatbot support.

---

##  Live Demo  
[Demo of website Interface](https://wael-a-alghamdi.github.io/Reception-robot-assistant/index.html)

---

##  Tech Used  
- HTML & CSS  
- PHP  
- IBM Watson Assistant  
- JSON (for chatbot skill export)

---

##  Features  
- Five control buttons: Forward, Left, Right, Stop, Backward  
- PHP backend for sending robot movement to database  
- Integrated chatbot in Arabic via Watson Assistant  
- Chatbot includes intents like jokes, personal info, commands, and fallback responses  
- Custom skill file (`skill-تحدث.json`) for Arabic interactions  

---

##  Notes  
- Requires server environment (e.g. XAMPP) for PHP pages  
- Background image is `html_background_image.jpg`  
- Watson Assistant chat loaded using public script from IBM  
- `skill-تحدث.json` can be imported directly into Watson Assistant

---

##  Project Overview (Arabic + English)

###  المقدمة – Introduction  
في هذا المشروع، تم إنشاء واجهة روبوت استقبال تحتوي على:

- صفحة تحكم (HTML & CSS) لحركات الروبوت  
- مساعد محادثة (Chat Assistant) باللغة العربية باستخدام Watson  
- تصدير المهارات كملف JSON وربطها بصفحة الويب  

In this project I created:
- An Arabic chat assistant  
- Exported the skill as JSON  
- Integrated it into the HTML robot control page

---

### 1. إنشاء Chat Assistant  
تم بناء مساعد محادثة باللغة العربية باستخدام IBM Watson Assistant.  
The chat assistant was created using IBM Watson and responds in Arabic.

---

### 2. التصدير الى JSON  
تم تصدير المهارة كملف JSON (`skill-تحدث.json`) لإعادة الاستخدام في مشاريع أخرى.  
The skill was exported as a JSON file for easy reuse.

---

### 3. ربط الشات مع صفحة HTML  
تم تضمين المساعد في صفحة التحكم الرئيسية مع أزرار الحركة.  
Chatbot was embedded directly in the HTML interface for real-time interaction.
