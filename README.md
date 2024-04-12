# TON Ruby SDK Project

This project demonstrates the usage of TON (Telegram Open Network) in Ruby by performing various operations using the `ton-sdk-ruby` and `ton-sdk-ruby-smc` gems.

## Installation

To get started with this project, you need to install the required gems:
`gem install ton-sdk-ruby`
`gem install ton-sdk-ruby-smc`

## Usage 
### Sending Transactions with Wallet V3
`require 'ton-sdk-ruby'
require 'ton-sdk-ruby-smc'

class TonSmc
  include TonSdkRuby
  include TonSdkRubySmc
  
  def send_wallet_v3
    # Your code for sending transactions with Wallet V3
  end
end

TonSmc.new.send_wallet_v3
`

### Sending Transactions with Wallet V4
`require 'ton-sdk-ruby'
require 'ton-sdk-ruby-smc'

class TonSmc
  include TonSdkRuby
  include TonSdkRubySmc
  
  def send_wallet_v4
    # Your code for sending transactions with Wallet V4
  end
end

TonSmc.new.send_wallet_v4
`
## ለመጀመር

1. ማከማቻውን `git clone https://github.com/samzhab/smart_contracts_playground_1.git`

2. ጥገኛዎችን ጫን፡ `bundle install`

3. ቦቱን ያሂዱ፡ `ruby smart_contracts.rb`

4. በቴሌግራም መተግበሪያዎ ውስጥ ከቦት ጋር ይገናኙ።

## Getting Started

1. Clone the repository: `git clone https://github.com/samzhab/smart_contracts_playground_1.git`

2. Install dependencies: `bundle install`

3. Run the bot: `ruby smart_contracts.rb`

4. Interact with the bot in your Telegram app.

## ፈቃድ
ይህ ስራ በ[Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/) ስር ፍቃድ ተሰጥቶታል።

![CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

መለያ፡ ይህ ፕሮጀክት በሳማኤል (AI Powered)፣ 2024 ታትሟል።

እርስዎ ለማድረግ ነፃ ነዎት፦
-  አጋራ  - ቁሳቁሱን በማንኛውም መካከለኛ ወይም ቅርጸት ይቅዱ እና እንደገና ያሰራጩ
-  ማላመድ  - ንብረቱን እንደገና ማደባለቅ ፣ መለወጥ እና በማንኛውም ዓላማ ለንግድም ቢሆን መገንባት።
-  አጋራ  - ቁሳቁሱን በማንኛውም መካከለኛ ወይም ቅርጸት ይቅዱ እና እንደገና ያሰራጩ
-  ማላመድ  - ንብረቱን እንደገና ማደባለቅ ፣ መለወጥ እና በማንኛውም ዓላማ ለንግድም ቢሆን መገንባት።

በሚከተለው ውል መሠረት፡-
-  መለያ — ተገቢውን ክሬዲት መስጠት፣ የፍቃዱ አገናኝ ማቅረብ እና ለውጦች መደረጉን መጠቆም አለቦት። በማንኛውም ምክንያታዊ መንገድ ሊያደርጉት ይችላሉ፣ ነገር ግን ፈቃድ ሰጪው እርስዎን ወይም አጠቃቀምዎን እንደሚደግፍ በሚጠቁም በማንኛውም መንገድ አይደለም።
- ሼር አላይክ — ቁሳቁሱን ካዋሃዱ፣ ከቀየሩ፣ ወይም ከገነቡት መዋጮዎን ከመጀመሪያው ባለው ፍቃድ ማሰራጨት አለቦት።

ምንም ተጨማሪ ገደቦች የሉም - ሌሎች ፈቃዱ የሚፈቅደውን ማንኛውንም ነገር እንዳያደርጉ በህጋዊ መንገድ የሚገድቡ ህጋዊ ውሎችን ወይም የቴክኖሎጂ እርምጃዎችን መተግበር አይችሉም።

ማሳሰቢያዎች፡-
በሕዝብ ጎራ ውስጥ ላሉ የቁስ አካላት ወይም አጠቃቀምዎ በሚመለከተው ልዩ ወይም ገደብ የተፈቀደበትን ፈቃድ ማክበር የለብዎትም።

ምንም ዋስትናዎች አልተሰጡም. ፈቃዱ ለታቀደው አገልግሎት አስፈላጊ የሆኑትን ሁሉንም ፈቃዶች ላይሰጥዎት ይችላል። ለምሳሌ፣ እንደ ህዝባዊነት፣ ግላዊነት ወይም የሞራል መብቶች ያሉ ሌሎች መብቶች ቁሱን እንዴት እንደሚጠቀሙ ሊገድቡ ይችላሉ።

## License
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

![CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

Attribution: This project is published by Samael (AI Powered), 2024.

You are free to:
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially.
Under the following terms:
- Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

Notices:
You do not have to comply with the license for elements of the material in the public domain or where your use is permitted by an applicable exception or limitation.

No warranties are given. The license may not give you all of the permissions necessary for your intended use. For example, other rights such as publicity, privacy, or moral rights may limit how you use the material.
