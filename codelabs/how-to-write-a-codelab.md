summary: Codelab ဘယ်လိုရေးမလဲ?
id: how-to-write-a-codelab
categories:
tags:
status: Published
authors: Arkar Min Tun
Feedback Link: https://github.com/GDGYangon/gdgyangon-codelabs/blob/main/codelabs/how-to-write-a-codelab.md

# Codelab ဘယ်လိုရေးမလဲ?

<!-- ------------------------ -->

## ဘာတွေပါဝင်သလဲ?

Duration: 1

- လိုအပ်သော libraries များ setup လုပ်နည်း
- Repositity ကူးယူပြီး setup လုပ်နည်း
- Codelab ရေးပုံရေးနည်း
- Contribute လုပ်နည်း

## လိုအပ်သော tools များ setup လုပ်နည်း

Duration: 10

Codelab တွေကို ကိုယ်တိုင်ပါဝင်ပြီး contribute လုပ်ဖို့အတွက်ဆို ဒီမှာပြောထားတဲ့ tools တွေ ကိုယ့်စက်ထဲမှာ သွင်းထားဖို့ လိုအပ်ပါလိမ့်မယ်။ အသေးစိတ် သွင်းဖို့ instruction တွေကို link တွေကနေ ဝင်ရောက်ပြီး ကြည့်ရှုနိုင်ပါတယ်။

1. go - [link](https://go.dev/dl/)
2. claat - [link](https://github.com/googlecodelabs/tools/tree/main/claat#install)
3. nodejs - [link](https://nodejs.org/en/blog/release/v14.17.3) version 14

Contribute လုပ်ဖို့အတွက် ဒီမှာ ပါတဲ့ tools တွေကို အကုန်နားလည်ဖို့ မလိုအပ်ပါဘူး။ အဓိက နားလည်ဖို့ လိုအပ်တာက `markdown` အသုံးအနှုံးတွေပဲ ဖြစ်ပါတယ်။ Markdown နဲ့ပတ်သက်ပြီး သိချင်တယ်ဆို [ဒီမှာ](https://www.markdownguide.org/cheat-sheet/) ဝင်ရောက်ပြီး ကြည့်ကြည့်လို့ရပါတယ်။

Editor အနေနဲ့တော့ vscode ကို အသုံးပြုဖို့ အကြံပြုချင်ပါတယ်။ markdown edit လုပ်ပြီး preview ကြည့်နိုင်တယ်ဆို တခြား editor တွေလဲ အသုံးပြုနိုင်ပါတယ်။

## Repositity ကူးယူပြီး setup လုပ်နည်း

Duration: 5

အဓိက contribute လုပ်ပေးနိုင်တဲ့ Github Repository ကတော့ [ဒီမှာ](https://github.com/GDGYangon/gdgyangon-codelabs) ပဲဖြစ်ပါတယ်။ ရှေ့အဆင့်မှာ ဖော်ပြထားတဲ့ tools တွေကို သွင်းပြီးပြီဆိုရင်တော့ ကိုယ့်ဆက်ထဲကို repository clone လုပ်ယူလိုက်ပါ။ Clone လုပ်ပြီးပြီဆိုရင်တော့ အောက်မှာ ပြထားတဲ့ command တွေကို run ပေးပြီး စတင်လို့ရပါပြီ။

- `node --version` - ကိုယ့်စက်ထဲမှာ လက်ရှိသွင်းထားတဲ့ node version ကို check ဖို့ အတွက် ဖြစ်ပါတယ်။ version 14 ကို အသုံးပြုဖို့ request လုပ်ပါတယ်။
- `npm install` - repository ထဲမှာ ပါဝင်တဲ့ node libraries တွေကို download ဆွဲဖို့အတွက် ဖြစ်ပါတယ်။ ဒီ command ကို run လိုက်တော့မှ ရှေ့ဆက်ပြီး command တွေ ထပ် run ဖို့ အဆင်ပြေမှာပဲ ဖြစ်ပါတယ်။

ကိုယ်က codelab အသစ်တခုကို စတင်မယ်ဆို အရင်ဆုံး [issue](https://github.com/GDGYangon/gdgyangon-codelabs/issues) မှာ ticket ဖွင့်ပေးဖို့ လိုအပ်ပါမယ်။ ticket ခေါင်းစဥ်ကိုတော့ ကိုယ်ရေးမယ့် codelab ခေါင်းစဥ်ပေးထားလို့ရပါတယ်။ Issue create လုပ်ပြီးရင်တော့ local မှာ branch ကို ticket id နဲ့ အတူတူပေးပေးပါ။ ဥပမာ `Codelab ဘယ်လိုရေးမလဲ?` ဆိုတဲ့ ticket ဖွင့်ပြီးတဲ့အချိန် github မှာ `Codelab ဘယ်လိုရေးမလဲ? #1` ဆိုပြီးပြနေတယ်ဆို `git checkout -b '#1'` ဆိုပြီး branch create လုပ်ပြီး codelab စတင်ရေးလို့ရပါပြီ။

## Codelab ရေးပုံရေးနည်း

Duration: 10

အစမှာပြောခဲ့သလိုပဲ codelab ရေးဖို့အတွက် markdown ကိုပဲ သိထားဖို့လိုပါတယ်။ Clone ထားတဲ့ repository ထဲမှာဆိုလဲ `codelabs` ဆိုတဲ့ folder ထဲမှာပဲ မိမိရဲ့ codelab ကို ရေးဖို့ လိုပါတယ်။

Codelab ရေးမယ်ဆို အရင်ဆုံး ခေါင်းစဥ်ကို english လို စဥ်းစားပြီး markdown file တခုကို `codelabs` folder ထဲမှာ create လုပ်ဖို့ လိုအပ်ပါမယ်။ ဥပမာ အခု file ကို `How to write a codelab` လို့ နာမည်ပေးမယ်ဆို file name ကို slug format နဲ့ `how-to-write-a-codelab.md` ဆိုပြီး နာမည်ပေးဖို့ လိုအပ်ပါမယ်။ extension `.md` ဆိုတာ `markdown` file ရဲ့ extension ပဲဖြစ်ပါတယ်။ မြန်မာလို နာမည်ပေးချင်း မပြုလုပ်ဖို့ တောင်းဆိုချင်ပါတယ်။ codelab အထဲမှာ မြန်မာလို အဝရေးလို့ရပါတယ်။

File create လုပ်ပြီးပြီဆိုရင်တော့ အရေးကြီးတဲ့ အစိတ်အပိုင်းတွေကို ရှင်းပြပေးပါရစေ။ ဒီမှာ ဖော်ပြထားတာကတော့ codelab တွေမှာ မပါမဖြစ်အစိတ်အပိုင်းတွေပဲ ဖြစ်ပါတယ်။

```
summary: Codelab ဘယ်လိုရေးမလဲ?
id: how-to-write-a-codelab
categories:
tags:
status: Published
authors: Arkar Min Tun
feedback link: https://github.com/GDGYangon/gdgyangon-codelabs/issues/new
```

- `summary` - Codelab ခေါင်းစဥ် ဖြစ်ပြီး codelab တွေ list အလိုက်ပြတဲ့နေရာမှာ အသုံးပြုပါတယ်။
- `id` - ဒါကတော့ ကိုယ့် codelab ရဲ့ unique id ပဲဖြစ်ပါတယ်။ file name နဲ့ အတူတူ ထားပေးလို့ရပါတယ်။
- `categories` - ဒါကတော့ ကိုယ်ရေးမယ့် codelab က ဘယ်နည်းပညာနဲ့ ပတ်သက်သလဲဆိုပြီး ထည့်ပေးဖို့ ဖြစ်ပါတယ်။ ဥပမာ android, web, chrome ဆိုပြီး တခုထက်ပိုပြီးလဲ comma ခံပြီး ထည့်ပေးလို့ရပါတယ်။
- `tags` - ဒါကတော့ codelab တွေကို ပြန်ပြီး filter လုပ်ဖို့ အသုံးပြုပါတယ်။ ဥပမာ Google IO မှာ ပြောသွားတဲ့ ခေါင်းစဥ်တွေကို ပြန်ပြီး တခုတစည်းထဲ tag တွဲပြီး လုပ်ထားတာမျိုးပါ။
- `authors` - ဒါကတော့ ဒီ codelab ကို အတူတကွ လုပ်ကြတဲ့သူတွေပါ။ ကိုယ်တိုင် ရေးထားတဲ့ codelab တွေအပြင် အခြားသူတွေ ရေးထားတဲ့ codelab တွေမှာလဲ ပြင်ဆင်စရာတွေ ရှိတဲ့အခါ ဝင်ရောက်ပြင်ပြီး မိမိရဲ့ contribution ကို ထည့်လို့ရပါတယ်။
- `feedback link` - ဒါကတော့ codelab နဲ့ပတ်သက်ပြီး ဆွေးနွေးတာတွေ လုပ်ချင်တယ်ဆို လုပ်ဖို့အတွက်ပါ။ Github repository မှာ issue အနေနဲ့ အသစ်ဖွင့်ပြီး ဆွေးနွေးတာတွေ ပြုလုပ်သွားနိုင်ပါတယ်။

အပေါ်ကအပိုင်းပြီးရင်တော့ စတင်ပြီး codelab ကို ရေးသားလို့ရပါပြီ။ Codelab အတွက် ပထမဆုံး ခေါင်းစဥ်ကို `#` နဲ့ ရေးသားရပါတယ်။ HTML မှာဆိုရင်တော့ `h1` heading အနေနဲ့ပါ။

```
# Codelab ဘယ်လိုရေးမလဲ?
```

ဒီအပိုင်းပြီးရင်တော့ codelab မှာ ပါဝင်မယ့် sections တွေကို `##` နဲ့ ရေးသားရပါတယ်။ ဒါနဲ့အတူ `Duration` ကိုပါ ထည့်ပေးရပါတယ်။ ဒီမှာ ထည့်ပေးရတဲ့ Duration ဆိုတာ ဒီ section ကို ပြီးမြောက်ဖို့ ကြာနိုင်တဲ့အချိန်ကို ခန့်မှန်းခြေ ထည့်ပေးထားရတာ ဖြစ်ပါတယ်။ Section တခုချင်းမှာပါတဲ့ Duration တွေကို စုပေါင်းပြီး browser ရဲ့ အပေါ် ညာဘက်ထောင့်မှာ codelab ရဲ့ စုစုပေါင်းကြာချိန်ကို ဖော်ပြပေးထားပါတယ်။

```
## လိုအပ်သော tools များ setup လုပ်နည်း

Duration: 10
```

ဒါပြီးသွားရင်တော့ ကျန်တဲ့အစိတ်အပိုင်းတွေကို markdown format အသုံးပြုပြီး ရေးသားလို့ရပါပြီ။ code snippet တွေထည့်မယ်ဆိုလဲ markdown reference ကိုကြည့်ပြီး ထည့်လို့ရပါတယ်။ ပုံတွေ video တွေ ထည့်မယ်ဆိုလဲ ထည့်လို့ရပါတယ်။ ပုံထည့်မယ်ဆို အရင်ဆုံး `codelabs > assets` folder ထဲမှာ codelab id နဲ့ folder လုပ်ပြီး ထည့်ပေးလို့ရပါတယ်။

```
Image Example

![alt-text-here](assets/how-to-write-a-codelab/puppy.jpg)
```

```
Video Example

[Youtube - GDG Yangon Playlists](https://www.youtube.com/@gdgygn/playlists)
```

## Contribute လုပ်နည်း

Duration: 2

Codelab ကို markdown format နဲ့ ရေးပြီးသွားပြီဆို local မှာ အရင် စမ်းကြည့်လို့ရပါတယ်။

```
cd codelabs
claat export [codelab.md]
npx gulp serve --codelabs-dir=codelabs
```

ပြီးရင် `localhost:8000` ကို browser ဖွင့်ကြည့်ပြီး ကိုယ့်ရဲ့ codelab ကို ဝင်ရောက်ပြီး ကြည့်လို့ရပါပြီ။ လိုအပ်တာတွေ ပြင်ပြီးရင်တော့ master branch ကို PR တင်ပြီး contribute လုပ်လို့ရပါပြီ။

Markdown file ကိုပြင်တိုင်း `claat export` ကို ပြန်ပြီး run ပေးဖို့ လိုအပ်ပါတယ်။
