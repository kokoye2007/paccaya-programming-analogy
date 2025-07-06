---
marp: true
theme: uncover
backgroundColor: #f0f0f0
color: #333
header: '၂၄ ပစ္စည်း နှင့် Programming Analogy'
footer: '© 2024 - Open Source Project'
paginate: true
style: |
  section {
    font-family: "Myanmar Sanpya", "Noto Sans", "Helvetica Neue", Arial, sans-serif;
    font-size: 90%;
    line-height: 1.6;
    letter-spacing: 0.1px;
  }

  h1, h2, h3 {
    font-weight: 600;
    margin-bottom: 0.4em;
  }

  ul {
    margin-top: 0.5em;
    padding-left: 1.4em;
  }

  li {
    margin-bottom: 0.3em;
  }

  small {
    font-size: 75%;
  }

  /* Optional: Burmese font fallback */
  body {
    font-family: "Myanmar Sanpya", "Noto Sans Myanmar", "Noto Sans", sans-serif;
  }

---

# **၂၄ ပစ္စည်း နှင့် Programming Analogy**

**ဗုဒ္ဓအဘိဓမ္မာ ပဋ္ဌာန်းတရားတော်ကို နည်းပညာဥပမာများဖြင့် လေ့လာခြင်း**

A Study of the 24 Patthana Conditions with Tech Analogies

---

## **၁။ ဟေတုပစ္စည်း (Hetu Paccayo)**
### Root-Condition

- **အနက်:** အမြစ်သဖွယ် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** အလောဘ, အဒေါသ (ကောင်းသောအမြစ်) က ကုသိုလ်စိတ်ကို ဖြစ်စေခြင်း။
- **Programming Analogy:** **Root Privilege / Core Algorithm Nature**
  - `sudo` ကဲ့သို့သော root အခွင့်အာဏာ (ဟေတု) က system-wide changes (အကျိုး) ကို ဖြစ်စေခြင်း။

---

## **၂။ အာရမ္မဏပစ္စည်း (Ārammaṇa Paccayo)**
### Object-Condition

- **အနက်:** အာရုံအဖြစ် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** အဆင်းကို မြင်စိတ်က အာရုံပြုခြင်း။
- **Programming Analogy:** **Input Data / Function Argument**
  - Function (စိတ်) သည် သူ့ထံ ပေးပို့လိုက်သော Input (အာရုံ) အပေါ်မှာသာ အလုပ်လုပ်ပြီး Output ထုတ်ပေးခြင်း။

---

## **၃။ အဓိပတိပစ္စည်း (Adhipati Paccayo)**
### Dominance-Condition

- **အနက်:** အကြီးအမှူးပြု၍၊ အစိုးရခြင်းဖြင့် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** ဆန္ဒ, ဝီရိယတို့က စိတ်ကို ဦးဆောင်ခြင်း။
- **Programming Analogy:** **Operating System Kernel / Main Controller**
  - Kernel (အဓိပတိ) သည် အခြား Process အားလုံး၏ အရင်းအမြစ်သုံးစွဲမှုကို အုပ်ချုပ်စီမံခြင်း။

---

## **၄။ အနန္တရပစ္စည်း (Anantara Paccayo)**
### Contiguity-Condition

- **အနက်:** အကြားမရှိ ဆက်တိုက်ဖြစ်ခြင်းဖြင့် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** ရှေ့စိတ်ချုပ်ပြီး နောက်စိတ်ချက်ချင်းဖြစ်ခြင်း။
- **Programming Analogy:** **CPU Instruction Cycle / Sequential Execution**
  - ရှေ့ Instruction ပြီးသည်နှင့် အကြားမရှိ နောက် Instruction ချက်ချင်း အလုပ်လုပ်ခြင်း။

---

## **၅။ သမနန္တရပစ္စည်း (Samanantara Paccayo)**
### Immediate Contiguity-Condition

- **အနက်:** ကောင်းစွာ အကြားမရှိ လမ်းဖွင့်ပေးခြင်းဖြင့် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** ရှေ့စိတ်က နောက်စိတ်ဖြစ်ရန် လမ်းကြောင်းဖွင့်ပေးခြင်း။
- **Programming Analogy:** **Command-line Pipelining (`|`)**
  - `ls` ၏ output က `grep` ၏ input အဖြစ် ချောမွေ့စွာကူးပြောင်းသွားပြီး အလုပ်လုပ်စေခြင်း။

---

## **၆။ သဟဇာတပစ္စည်း (Sahajāta Paccayo)**
### Co-nascence-Condition

- **အနက်:** အတူတကွ ဖြစ်ခြင်းဖြင့် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** မီးတောက်နှင့် အလင်းရောင် အတူဖြစ်ခြင်း။
- **Programming Analogy:** **Object and its Instance Variables**
  - Object တစ်ခုကို instantiate လုပ်လိုက်လျှင် ၎င်း object (စိတ်) နှင့် ၎င်း၏ properties (စေတသိက်) တို့ တစ်ပြိုင်နက်တည်း ဖြစ်ပေါ်လာခြင်း။

---

## **၇။ အညမညပစ္စည်း (Aññamañña Paccayo)**
### Reciprocity-Condition

- **အနက်:** အချင်းချင်း အပြန်အလှန် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** ထောက်တိုင် ၃ ချောင်း အပြန်အလှန်မှီခိုခြင်း။
- **Programming Analogy:** **Mutual Recursion / Client-Server Communication**
  - Function A က B ကိုခေါ်၊ B က A ကိုပြန်ခေါ်ခြင်း။ Client က Server ကို၊ Server က Client ကို အပြန်အလှန် မှီခိုခြင်း။

---

## **၈။ နိဿယပစ္စည်း (Nissaya Paccayo)**
### Support / Foundation-Condition

- **အနက်:** မှီရာအုတ်မြစ်အဖြစ် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** သစ်ပင်က မြေကြီးကို မှီခိုခြင်း။
- **Programming Analogy:** **Hardware and Software**
  - Software (နာမ်) သည် CPU, RAM ဆိုသည့် Hardware (ရုပ်) ကို မမှီခိုဘဲ လုံးဝ run ၍မရခြင်း။

---

## **၉။ ဥပနိဿယပစ္စည်း (Upanissaya Paccayo)**
### Decisive Support-Condition

- **အနက်:** အားကြီးသောအကြောင်းအဖြစ် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** သဒ္ဓါတရားကြောင့် ဒါနပြုခြင်း။
- **Programming Analogy:** **Frameworks (e.g., React, .NET)**
  - Application တစ်ခုသည် Framework တစ်ခုကို အားကြီးစွာ မှီခိုပြီး တည်ဆောက်ထားရခြင်း။

---

## **၁၀။ ပုရေဇာတပစ္စည်း (Purejāta Paccayo)**
### Pre-nascence-Condition

- **အနက်:** ရှေ့ကဦးစွာဖြစ်နှင့်ပြီး ကျေးဇူးပြုခြင်း။
- **နမူနာ:** မျက်စိရှိနှင့်မှ မြင်စိတ်ဖြစ်ခြင်း။
- **Programming Analogy:** **Initialization**
  - Variable ကို initialize လုပ်နှင့်ပြီးမှသာ ထို variable ကို အသုံးပြုနိုင်ခြင်း။

---

## **၁၁။ ပစ္ဆာဇာတပစ္စည်း (Pacchājāta Paccayo)**
### Post-nascence-Condition

- **အနက်:** နောက်မှဖြစ်သောတရားက ရှေ့ကဖြစ်နှင့်သောတရားကို ထောက်ပံ့ခြင်း။
- **နမူနာ:** နောက်ဖြစ်သောစိတ်က ရှေ့ရုပ်ကို ထောက်ပံ့ခြင်း။
- **Programming Analogy:** **Keep-Alive Signal**
  - ရှေ့ကတည်ရှိနေသော Network Connection ကို နောက်မှပုံမှန်ပို့ပေးနေသော Heartbeat/Ping က ထောက်ပံ့ရှင်သန်စေခြင်း။

---

## **၁၂။ အာသေဝနပစ္စည်း (Āsevana Paccayo)**
### Repetition-Condition

- **အနက်:** အဖန်တလဲလဲ ဖြစ်ခြင်းဖြင့် နောက်ဖြစ်မည့်တရားကို အားကောင်းစေခြင်း။
- **နမူနာ:** စာကို ထပ်ကျက်၍ ကျွမ်းကျင်ခြင်း။
- **Programming Analogy:** **Loops (for, while) / Machine Learning Training**
  - Loop ကို အထပ်ထပ် run ခြင်းဖြင့် တန်ဖိုးတစ်ခုကို အားကောင်းစေခြင်း။ Model ကို အထပ်ထပ် train ခြင်းဖြင့် ပိုတိကျစေခြင်း။

---

## **၁၃။ ကမ္မပစ္စည်း (Kamma Paccayo)**
### Action / Kamma-Condition

- **အနက်:** ပြုလုပ်အားထုတ်ခြင်း (စေတနာ) ဖြင့် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** စေတနာကံကြောင့် အကျိုးဖြစ်ခြင်း။
- **Programming Analogy:** **Executing a Script / Triggering an Event**
  - User က Button နှိပ်လိုက်ခြင်း (ကံ) ကြောင့် data save သွားခြင်း (အကျိုး)။

---

## **၁၄။ ဝိပါကပစ္စည်း (Vipāka Paccayo)**
### Result-Condition

- **အနက်:** အကျိုးတရားအဖြစ် ငြိမ်သက်စွာဖြစ်ခြင်းဖြင့် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** ကံ၏အကျိုး မြင်စိတ်၊ ကြားစိတ်ဖြစ်ခြင်း။
- **Programming Analogy:** **Return Value / Function Output**
  - Function (ကမ္မ) ကို run ပြီးနောက် ရလာသော ပြန်တန်ဖိုး (ဝိပါက)။

---

## **၁၅။ အာဟာရပစ္စည်း (Āhāra Paccayo)**
### Nutriment-Condition

- **အနက်:** ထောက်ပံ့ခိုင်မာစေခြင်းဖြင့် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** အစာက ရုပ်ကို၊ ဖဿက နာမ်ကို ထောက်ပံ့ခြင်း။
- **Programming Analogy:** **Electricity & System Resources**
  - လျှပ်စစ် (ရုပ်အာဟာရ) က Hardware ကို ထောက်ပံ့ပြီး၊ CPU Time/RAM (နာမ်အာဟာရ) က Process ကို ထောက်ပံ့ခြင်း။

---

## **၁၆။ ဣန္ဒြိယပစ္စည်း (Indriya Paccayo)**
### Faculty / Control-Condition

- **အနက်:** မိမိ၏အရာ၌ အစိုးရခြင်းဖြင့် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** မျက်စိက မြင်မှု၌ အစိုးရခြင်း။
- **Programming Analogy:** **Hardware Drivers**
  - Graphics Driver က display ကိုသာ အစိုးရပြီး၊ Sound Driver က audio ကိုသာ အစိုးရခြင်း။

---

## **၁၇။ ဈာနပစ္စည်း (Jhāna Paccayo)**
### Jhāna-Factor-Condition

- **အနက်:** အာရုံတစ်ခုတည်းသို့ စူးစိုက်စေခြင်းဖြင့် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** ဝိတက်က စိတ်ကို အာရုံပေါ်တင်ပေးခြင်း။
- **Programming Analogy:** **Mutex / Resource Lock**
  - Thread တစ်ခုက Resource ကို Lock ချပြီး အလုပ်လုပ်နေချိန်မှာ အခြား Thread များကို ဝင်မလာအောင် စူးစိုက်စေခြင်း။

---

## **၁၈။ မဂ္ဂပစ္စည်း (Magga Paccayo)**
### Path-Condition

- **အနက်:** သံသရာမှ ထွက်မြောက်ရာလမ်းကြောင်းအဖြစ် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** မဂ္ဂင်က နိဗ္ဗာန်သို့ ပို့ဆောင်ခြင်း။
- **Programming Analogy:** **Routing / Execution Path**
  - Network Router က Data Packet များကို လမ်းကြောင်းရှာပေးခြင်း။

---

## **၁၉။ သမ္ပယုတ္တပစ္စည်း (Sampayutta Paccayo)**
### Association-Condition

- **အနက်:** အတူဖြစ်၊ အတူချုပ်၊ အတူမှီ၊ အာရုံတစ်ခုတည်းရှိခြင်းဖြင့် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** စိတ်နှင့် စေတသိက် ရောနှောဖြစ်ခြင်း။
- **Programming Analogy:** **Tight Coupling / OOP Class**
  - Class တစ်ခု၏ methods နှင့် properties တို့ ခွဲမရအောင် ပေါင်းစပ်တည်ရှိခြင်း။

---

## **၂၀။ ဝိပ္ပယုတ္တပစ္စည်း (Vippayutta Paccayo)**
### Dissociation-Condition

- **အနက်:** သဘောမတူဘဲ ခွဲခြား၍ ကျေးဇူးပြုခြင်း။
- **နမူနာ:** နာမ်နှင့်ရုပ် အချင်းချင်း ကျေးဇူးပြုခြင်း။
- **Programming Analogy:** **Loose Coupling / Frontend-Backend Separation**
  - UI (ရုပ်) နှင့် Server Logic (နာမ်) တို့ သီးခြားစီဖြစ်သော်လည်း အပြန်အလှန် ကျေးဇူးပြုခြင်း။

---

## **၂၁။ အတ္ထိပစ္စည်း (Atthi Paccayo)**
### Presence-Condition

- **အနက်:** ထင်ရှားရှိနေခြင်းဖြင့် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** နေရှိနေ၍ အလင်းရောင်ဖြစ်ခြင်း။
- **Programming Analogy:** **Server Uptime / Active Connection**
  - Server run နေခြင်း (အတ္ထိ) ကြောင့် Website ကို ကြည့်ရှုနိုင်ခြင်း (အကျိုး)။

---

## **၂၂။ နတ္ထိပစ္စည်း (Natthi Paccayo)**
### Absence-Condition

- **အနက်:** ချုပ်ပျောက်သွားခြင်းဖြင့် နောက်တရားဖြစ်ရန် နေရာပေး၍ ကျေးဇူးပြုခြင်း။
- **နမူနာ:** ရှေ့စိတ်ချုပ်၍ နောက်စိတ်ဖြစ်ခြင်း။
- **Programming Analogy:** **Releasing a Lock**
  - Process A က Lock (ရှေ့စိတ်) ကို လွှတ်ပေးလိုက်မှ (ချုပ်ပျောက်သွားမှ) Process B (နောက်စိတ်) က ထို Lock ကို ရယူနိုင်ခြင်း။

---

## **၂၃။ ဝိဂတပစ္စည်း (Vigata Paccayo)**
### Disappearance-Condition

- **အနက်:** ကင်းစင်ချုပ်ပျောက်သွားခြင်းဖြင့် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** မီးငြိမ်း၍ အမှောင်ဖြစ်ခြင်း။
- **Programming Analogy:** **Process Termination freeing RAM**
  - Process တစ်ခု (ရှေ့စိတ်) terminate ဖြစ်၍ RAM လွတ်သွားမှ (ကင်းစင်သွားမှ) တခြား Process က အသုံးပြုနိုင်ခြင်း။

---

## **၂၄။ အဝိဂတပစ္စည်း (Avigata Paccayo)**
### Non-disappearance-Condition

- **အနက်:** မကင်းကွာဘဲ ထင်ရှားရှိနေခြင်းဖြင့် ကျေးဇူးပြုခြင်း။
- **နမူနာ:** သမုဒ္ဒရာရှိ၍ သတ္တဝါမှီခိုနိုင်ခြင်း။
- **Programming Analogy:** **Power Grid / Core Infrastructure**
  - လျှပ်စစ်ဓာတ်အားလိုင်း (အဝိဂတ) မပျောက်ကွယ်ဘဲ တည်ရှိနေသရွေ့ Data Center များ အလုပ်လုပ်နိုင်ခြင်း။

---


# **Thank You & Contributions Welcome!**

**GitHub:** `kokoye2007/paccaya-programming-analogy`

**License:** Creative Commons (CC-BY-SA 4.0)

**Font:** Myanmar Sanpya - Google (Apache License, Version 2.0)
