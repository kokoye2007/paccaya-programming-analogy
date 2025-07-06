# ၂၄ ပစ္စည်း နှင့် Programming Analogy

ဤစီမံကိန်းသည် ဗုဒ္ဓအဘိဓမ္မာတွင် လာရှိသော ၂၄ ပစ္စည်း ပဋ္ဌာန်းတရားတော်၏ နက်နဲသော သဘောတရားများကို မျက်မှောက်ခေတ် Programmer များ၊ နည်းပညာရှင်များ ပိုမိုနားလည်လွယ်ကူစေရန် Programming Concepts များဖြင့် ယှဉ်တွဲရှင်းလင်းထားသော Open Source Project တစ်ခု ဖြစ်ပါသည်။

This project is an open-source initiative to explain the profound concepts of the 24 Patthana Conditions from Buddhist Abhidhamma by drawing analogies with modern programming concepts, making them more accessible to developers and tech enthusiasts.

## အကျဉ်းချုပ် ဇယားကွက် (Summary Table)

| အမှတ် | ပစ္စည်းအမည် | အနက် (Meaning) | နမူနာ (၁) - အထွေထွေ | နမူနာ (၂) - နည်းပညာ (Programming Analogy) |
| :--- | :--- | :--- | :--- | :--- |
| **၁** | **ဟေတု** | အမြစ်/Root | အလောဘ, အဒေါသ (ကောင်းသောအမြစ်) က ကုသိုလ်စိတ်ကို ဖြစ်စေခြင်း။ | **Root Privilege/Core Algorithm Nature:** `sudo` ကဲ့သို့သော root အခွင့်အာဏာ (ဟေတု) က system-wide changes (အကျိုး) ကို ဖြစ်စေခြင်း။ |
| **၂** | **အာရမ္မဏ** | အာရုံ/Object | အဆင်းကို မြင်စိတ်က အာရုံပြုခြင်း။ | **Input Data / Function Argument:** Function (စိတ်) သည် သူ့ထံ ပေးပို့လိုက်သော Input (အာရုံ) အပေါ်မှာသာ အလုပ်လုပ်ပြီး Output ထုတ်ပေးခြင်း။ |
| **၃** | **အဓိပတိ** | အကြီးအမှူး/Dominance | ဆန္ဒ, ဝီရိယတို့က စိတ်ကို ဦးဆောင်ခြင်း။ | **Operating System Kernel / Main Controller:** Kernel (အဓိပတိ) သည် အခြား Process အားလုံး၏ အရင်းအမြစ်သုံးစွဲမှုကို အုပ်ချုပ်စီမံခြင်း။ |
| **၄** | **အနန္တရ** | အကြားမရှိ/Contiguity | ရှေ့စိတ်ချုပ်ပြီး နောက်စိတ်ချက်ချင်းဖြစ်ခြင်း။ | **CPU Instruction Cycle / Sequential Execution:** ရှေ့ Instruction ပြီးသည်နှင့် အကြားမရှိ နောက် Instruction ချက်ချင်း အလုပ်လုပ်ခြင်း။ |
| **၅** | **သမနန္တရ** | လမ်းဖွင့်ပေးခြင်း/Immediate Contiguity | ရှေ့စိတ်က နောက်စိတ်ဖြစ်ရန် လမ်းကြောင်းဖွင့်ပေးခြင်း။ | **Command-line Pipelining (`|`):** `ls` ၏ output က `grep` ၏ input အဖြစ် ချောမွေ့စွာကူးပြောင်းသွားပြီး အလုပ်လုပ်စေခြင်း။ |
| **၆** | **သဟဇာတ** | အတူဖြစ်ခြင်း/Co-nascence | မီးတောက်နှင့် အလင်းရောင် အတူဖြစ်ခြင်း။ | **Object and its Instance Variables:** Object တစ်ခုကို instantiate လုပ်လိုက်လျှင် ၎င်း object (စိတ်) နှင့် ၎င်း၏ properties (စေတသိက်) တို့ တစ်ပြိုင်နက်တည်း ဖြစ်ပေါ်လာခြင်း။ |
| **၇** | **အညမည** | အပြန်အလှန်/Reciprocity | ထောက်တိုင် ၃ ချောင်း အပြန်အလှန်မှီခိုခြင်း။ | **Mutual Recursion / Client-Server Communication:** Function A က B ကိုခေါ်၊ B က A ကိုပြန်ခေါ်ခြင်း။ Client က Server ကို၊ Server က Client ကို အပြန်အလှန် မှီခိုခြင်း။ |
| **၈** | **နိဿယ**| မှီရာအုတ်မြစ်/Support, Foundation | သစ်ပင်က မြေကြီးကို မှီခိုခြင်း။ | **Hardware and Software:** Software (နာမ်) သည် CPU, RAM ဆိုသည့် Hardware (ရုပ်) ကို မမှီခိုဘဲ လုံးဝ run ၍မရခြင်း။ |
| **၉** | **ဥပနိဿယ** | အားကြီးသောအကြောင်း/Decisive Support | သဒ္ဓါတရားကြောင့် ဒါနပြုခြင်း။ | **Frameworks (e.g., React, .NET):** Application တစ်ခုသည် Framework တစ်ခုကို အားကြီးစွာ မှီခိုပြီး တည်ဆောက်ထားရခြင်း။ |
| **၁၀** | **ပုရေဇာတ** | ရှေ့ကဖြစ်နှင့်ခြင်း/Pre-nascence | မျက်စိရှိနှင့်မှ မြင်စိတ်ဖြစ်ခြင်း။ | **Initialization:** Variable ကို initialize လုပ်နှင့်ပြီးမှသာ ထို variable ကို အသုံးပြုနိုင်ခြင်း။ |
| **၁၁**| **ပစ္ဆာဇာတ**| နောက်ကထောက်ပံ့ခြင်း/Post-nascence | နောက်ဖြစ်သောစိတ်က ရှေ့ရုပ်ကို ထောက်ပံ့ခြင်း။ | **Keep-Alive Signal:** ရှေ့ကတည်ရှိနေသော Network Connection ကို နောက်မှပုံမှန်ပို့ပေးနေသော Heartbeat/Ping က ထောက်ပံ့ရှင်သန်စေခြင်း။ |
| **၁၂**| **အာသေဝန** | ထပ်ခါထပ်ခါ/Repetition | စာကို ထပ်ကျက်၍ ကျွမ်းကျင်ခြင်း။ | **Loops (for, while) / Machine Learning Training:** Loop ကို အထပ်ထပ် run ခြင်းဖြင့် တန်ဖိုးတစ်ခုကို အားကောင်းစေခြင်း။ Model ကို အထပ်ထပ် train ခြင်းဖြင့် ပိုတိကျစေခြင်း။ |
| **၁၃**| **ကမ္မ**| ပြုလုပ်မှု/Action, Kamma | စေတနာကံကြောင့် အကျိုးဖြစ်ခြင်း။ | **Executing a Script / Triggering an Event:** User က Button နှိပ်လိုက်ခြင်း (ကံ) ကြောင့် data save သွားခြင်း (အကျိုး)။ |
| **၁၄**| **ဝိပါက**| အကျိုး/Result | ကံ၏အကျိုး မြင်စိတ်၊ ကြားစိတ်ဖြစ်ခြင်း။ | **Return Value / Function Output:** Function (ကမ္မ) ကို run ပြီးနောက် ရလာသော ပြန်တန်ဖိုး (ဝိပါက)။ |
| **၁၅**| **အာဟာရ** | အာဟာရ/Nutriment | အစာက ရုပ်ကို၊ ဖဿက နာမ်ကို ထောက်ပံ့ခြင်း။ | **Electricity & System Resources:** လျှပ်စစ် (ရုပ်အာဟာရ) က Hardware ကို ထောက်ပံ့ပြီး၊ CPU Time/RAM (နာမ်အာဟာရ) က Process ကို ထောက်ပံ့ခြင်း။ |
| **၁၆**| **ဣန္ဒြိယ**| အစိုးရခြင်း/Faculty, Control | မျက်စိက မြင်မှု၌ အစိုးရခြင်း။ | **Hardware Drivers:** Graphics Driver က display ကိုသာ အစိုးရပြီး၊ Sound Driver က audio ကိုသာ အစိုးရခြင်း။ |
| **၁၇**| **ဈာန** | စူးစိုက်စေခြင်း/Jhāna Factor | ဝိတက်က စိတ်ကို အာရုံပေါ်တင်ပေးခြင်း။ | **Mutex / Resource Lock:** Thread တစ်ခုက Resource ကို Lock ချပြီး အလုပ်လုပ်နေချိန်မှာ အခြား Thread များကို ဝင်မလာအောင် စူးစိုက်စေခြင်း။ |
| **၁၈**| **မဂ္ဂ** | လမ်းကြောင်း/Path | မဂ္ဂင်က နိဗ္ဗာန်သို့ ပို့ဆောင်ခြင်း။ | **Routing / Execution Path:** Network Router က Data Packet များကို လမ်းကြောင်းရှာပေးခြင်း။ |
| **၁၉**| **သမ္ပယုတ္တ** | ရောနှောပေါင်းစပ်ခြင်း/Association | စိတ်နှင့် စေတသိက် ရောနှောဖြစ်ခြင်း။ | **Tight Coupling / OOP Class:** Class တစ်ခု၏ methods နှင့် properties တို့ ခွဲမရအောင် ပေါင်းစပ်တည်ရှိခြင်း။ |
| **၂၀**| **ဝိပ္ပယုတ္တ** | မရောဘဲကျေးဇူးပြုခြင်း/Dissociation | နာမ်နှင့်ရုပ် အချင်းချင်း ကျေးဇူးပြုခြင်း။ | **Loose Coupling / Frontend-Backend Separation:** UI (ရုပ်) နှင့် Server Logic (နာမ်) တို့ သီးခြားစီဖြစ်သော်လည်း အပြန်အလှန် ကျေးဇူးပြုခြင်း။ |
| **၂၁**| **အတ္ထိ**| ရှိနေခြင်း/Presence | နေရှိနေ၍ အလင်းရောင်ဖြစ်ခြင်း။ | **Server Uptime / Active Connection:** Server run နေခြင်း (အတ္ထိ) ကြောင့် Website ကို ကြည့်ရှုနိုင်ခြင်း (အကျိုး)။ |
| **၂၂**| **နတ္ထိ**| ချုပ်ပျောက်၍ နေရာပေးခြင်း/Absence | ရှေ့စိတ်ချုပ်၍ နောက်စိတ်ဖြစ်ခြင်း။ | **Releasing a Lock:** Process A က Lock (ရှေ့စိတ်) ကို လွှတ်ပေးလိုက်မှ (ချုပ်ပျောက်သွားမှ) Process B (နောက်စိတ်) က ထို Lock ကို ရယူနိုင်ခြင်း။ |
| **၂၃**| **ဝိဂတ**| ကင်းစင်၍ နေရာပေးခြင်း/Disappearance | မီးငြိမ်း၍ အမှောင်ဖြစ်ခြင်း။ | **Process Termination freeing RAM:** Process တစ်ခု (ရှေ့စိတ်) terminate ဖြစ်၍ RAM လွတ်သွားမှ (ကင်းစင်သွားမှ) တခြား Process က အသုံးပြုနိုင်ခြင်း။ |
| **၂၄**| **အဝိဂတ**| မကင်းကွာ ရှိနေခြင်း/Non-disappearance | သမုဒ္ဒရာရှိ၍ သတ္တဝါမှီခိုနိုင်ခြင်း။ | **Power Grid / Core Infrastructure:** လျှပ်စစ်ဓာတ်အားလိုင်း (အဝိဂတ) မပျောက်ကွယ်ဘဲ တည်ရှိနေသရွေ့ Data Center များ အလုပ်လုပ်နိုင်ခြင်း။ |

## ပါဝင်ကူညီခြင်း (Contribution)

ဤစီမံကိန်းသည် အများပြည်သူ ပါဝင်ကူညီနိုင်ရန် လမ်းဖွင့်ပေးထားပါသည်။ အကြံပြုချက်များ၊ ပြင်ဆင်ချက်များ၊ ပိုမိုကောင်းမွန်သော ဥပမာများကို ကြိုဆိုပါသည်။ အသေးစိတ်ကို [CONTRIBUTING.md](CONTRIBUTING.md) တွင် ဖတ်ရှုနိုင်ပါသည်။

## လိုင်စင် (License)

ဤအချက်အလက်များကို [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/) ဖြင့် မျှဝေပါသည်။

---
[View as a Slideshow](https://kokoye2007.github.io/paccaya-programming-analogy/) 

<!-- You will need to create and export the slides.html from Marp -->
