# 3 мавзӯи асосӣ
### Scope
### Hoisting
### TDZ

# Scope

Дар скрипти java, миқёс дастрасии функсияҳо ва объектҳои тағирёбандаро дар қисмҳои гуногуни код муайян мекунад

# Scope types:
## Global scope
## Local scope
### Function scope
### block scope
## Module scope

# Нақши Global Scope

-Миқёси глобалӣ: Миқёси глобалӣ доираи васеи дастрас аст. Тағйирёбандаҳое, ки дар миқёси глобалӣ эълон шудаанд, аз ҳар ҷои коди шумо дастрасанд, хоҳ он дар дохили функсияҳо, изҳороти шартӣ, ҳалқаҳо ё дигар блокҳои код.

-Берун аз ягон функсия ё блок

-Тағйирёбандаҳои дар миқёси ҷаҳонӣ эълоншуда дар ҳама ҷо дастрасанд

-Контексти глобалии иҷро контексти аввалияест, ки ҳар вақте ки коди JavaScript барои иҷро бор карда мешавад, эҷод мешавад. Он доираи асосиро ифода мекунад, ки дар он тағирёбандаҳо, функсияҳо ва объектҳо дар доираи барнома фаъолият мекунанд.

Контексти глобалӣ дорои тағирёбандаҳои глобалӣ, функсияҳо ва дигар объектҳое мебошад, ки дар тамоми барнома дастрасанд.

# Function Scope

-Миқёси функсия: Миқёсе, ки бо функсия сохта шудааст. Инчунин доираи маҳаллӣ номида мешавад

-Тағйирёбандаҳо танҳо дар дохили функсия дастрасанд, НА берун аз он

-Миқёси функсия дар JavaScript ба доираи тағирёбандаҳо ва функсияҳое дахл дорад, ки дар дохили функсия муайян карда шудаанд. Тағйирёбандаҳо ва функсияҳое, ки бо калимаи калидии var эълон шудаанд, доираи функсия доранд.

-Тағйирёбандаҳое, ки дар дохили функсия эълон шудаанд, танҳо дар дохили он функсия ва ҳама гуна функсияҳои лона дастрасанд. Онҳо берун аз функсияе, ки дар он муайян шудаанд, дастрас нестанд. Ин маънои онро дорад, ки тағирёбандаҳои дар дохили функсия эълоншуда пеш аз эъломияи онҳо ё берун аз функсия дастрас нестанд.

# Block Scope
-Миқёси блок дар JavaScript ба миқёси тағирёбандаҳо ва функсияҳое дахл дорад, ки дар дохили блоки код муайян карда шудаанд, масалан дар дохили як ҷуфт қавсҳои ҷингила {}. Тағйирёбандаҳо ва функсияҳое, ки бо калимаҳои калидии let ва const эълон шудаанд, доираи блоки доранд. Онҳо берун аз функсияе, ки дар он муайян шудаанд, дастрас нестанд. Ин маънои онро дорад, ки тағирёбандаҳои дар дохили функсия эълоншуда пеш аз эъломияи онҳо ё берун аз функсия дастрас нестанд.

-Тағйирёбандаҳо танҳо дар дохили блок дастрасанд (миқёси блок)

-АММО, ин танҳо ба тағирёбандаҳои let ва const дахл дорад

-Функсияҳо инчунин маҳдуд карда мешаванд (танҳо дар ҳолати қатъӣ)

# Hoisting чист?

-Hoisting як механизми JavaScript мебошад, ки дар он тағирёбандаҳо ва эъломияҳои функсия пеш аз иҷрои код ба болои доираи онҳо интиқол дода мешаванд.

-Histing дар JavaScript рафторест, ки дар он функсия ё тағирёбанда пеш аз эъломия истифода мешавад.

-Бо тағирёбандаҳои var эълоншуда, эъломияи тағирёбанда баланд мешавад, аммо бо арзиши пешфарз -и номуайян

-эъломияҳои функсия бо арзиши он бардошта мешаванд ва онҳоро дар ҳама ҷо дар доираи он даъват кардан мумкин аст