﻿#ഫങ്ഷൻ 
നമ്മുടെ കരെല്‍ വലതു വശത്തേക്ക് തിരിയണം എന്ന് വയ്ക്കുക. നമുക്ക് എങ്ങിനെ നിര്‍ദേശങ്ങള്‍ കൊടുക്കാം. നിങ്ങള്‍ക്ക് പ്രോഗ്രാമ്മറുടെ ചിന്താരീതി ഉണ്ടെങ്കില്‍ പെട്ടെന്ന്‍ തന്നെ പറയാന്‍ പറ്റും.

ഉത്തരം ലളിതം ആണ്. മൂന്ന് പ്രാവശ്യം ഇടത്തോട്ട് തിരിഞ്ഞാല്‍ വലത്തോട്ട് തിരിഞ്ഞപോലെയായി. 

<code 3 turnLefts()>
അങ്ങനെ 3 ഇടത്തോട്ട് തിരിയാനുള്ള നിര്‍ദേശങ്ങള്‍ ആണ് വലത്തോട്ട് തിരിയാന്‍ ഉള്ളത് എന്ന് നമുക്ക് ഇപ്പോള്‍ അറിയാം. 2 കൊല്ലം കഴിഞ്ഞു വേറെ ഒരാള്‍ നമ്മള്‍ എഴുതിയ പ്രോഗ്രാം നോക്കുമ്പോള്‍ അയാള്‍ക്ക് ഒറ്റനോട്ടത്തില്‍അത് മനസിലായിക്കോളും എന്നില്ല, കുറച്ചു സമയം അയാള്‍ ചിന്തിച്ചാല്‍, അല്ലെങ്കില്‍ ഓരോ സ്റ്റെപ്പുകള്‍ ആയി എങ്ങിനെ പ്രോഗ്രാം പ്രവര്‍ത്തിക്കും എന്ന് നോക്കിയാല്‍ അയാള്‍ക്ക് മനസിലാകും. 

ഇത് ഒരു ചെറിയ ഉദാഹരണം മാത്രമാണ്. ശരിക്കും വലിയ പ്രോഗ്രാമുകള്‍ എഴുതുമ്പോള്‍ ഇതല്ല സ്ഥിതി. പുതിയ ആള്‍ കഠിനമായി പരിശ്രമിച്ചാലേ വല്ലതും മനസിലാകൂ. അപ്പോള്‍ അതിനു എന്താണ് ഒരു പ്രതിവിധി?

ഒരു കാര്യം അല്ലെങ്കില്‍ പൂര്‍ണമായ പ്രവൃത്തി ചെയ്യുന്ന നിര്‍ദേശങ്ങള്‍ എല്ലാം ഒരു കൂട്ടം ആയി വച്ചിട്ട് അതിനു അര്‍ത്ഥപൂര്‍ണമായ ഒരു പേരുകൊടുത്തു അത് ഒരു നിര്‍ദേശം ആക്കിയാല്‍ പോരെ? അങ്ങിനെ നിര്‍ദേശങ്ങളുടെ ഒരു കൂട്ടത്തെയാണ് ഫങ്ഷന്‍ എന്ന് പറയുന്നത്.

ഇവിടെ നോക്കുകയാണെങ്കില്‍, 3 ഇടത്തോട്ട് തിരിയാനുള്ള നിര്‍ദേശങ്ങളെ ചേര്‍ത്തു വലത്തോട്ട് തിരിയാനുള്ള ഒരു ഫങ്ഷന്‍ ഉണ്ടാക്കാം. ഫങ്ഷന്‍ പിന്നെ ഒരു നിര്‍ദേശം പോലെ ഉപയോഗിക്കാം. ആ വലത്തോട്ട് തിരിയാനുള്ള നിര്‍ദേശം ഭാവിയില്‍ വരുന്ന പ്രോഗ്രാമ്മര്‍ നോക്കുമ്പോള്‍ അയാള്‍ക്ക് എളുപ്പം അര്‍ത്ഥം മനസിലാക്കാന്‍ പറ്റും.

<code function turnRight()>

##ഫങ്ഷന്‍റെ സ്വഭാവനിയന്ത്രണം
ഇംഗ്ലീഷില്‍ ഫങ്ഷനിലേക്ക് പരാമെറ്റര്‍ കൊടുക്കുക എന്ന് പറയും. മുകളില്‍ പറഞ്ഞപോലെ ഒരു ഫങ്ഷന്‍ എഴുതിയാല്‍ അത് ഒരു കാര്യം ഒരേ പോലെയാണ് എപ്പോള്‍ വിളിച്ചാലും ചെയ്യുക. വിളിക്കുന്നതിനു അനുസരിച് ചെയ്യുന്ന കാര്യത്തിന്‍റെ സ്വഭാവം കുറച്ചു മാറ്റണം എന്നുണ്ടെങ്കില്‍ നമുക്ക് വിളിക്കുമ്പോള്‍ പരാമെറ്റര്‍ ആയി വിവിധ ഡാറ്റകള്‍/ചരങ്ങള്‍ കൊടുക്കാം.

നിത്യജീവിതത്തിലെ ഒരു ഉദാഹരണത്തിലെക്ക് വരാം. നമ്മള്‍ ചായക്കടയില്‍ പോയി അവിടെയുള്ള സപ്ലൈ ചെയ്യുന്ന ആളോട് ചായ എന്ന് പറയുന്നു. വെറുതെ ചായ എന്ന് പറഞ്ഞാല്‍ അത് എങ്ങിനെ ഉണ്ടാക്കണം എന്നുള്ള നിര്‍ദേശങ്ങള്‍ അവിടെ  അടുക്കളയില്‍ ചായ ഉണ്ടാക്കുന്ന ആള്‍ക്ക് അറിയാം. അതുപോലെ ചായ ഉണ്ടാക്കി നമുക്ക് കിട്ടും. ഇതിനെ നമുക്ക് ഒരു ഫങ്ഷന്‍ ആയി പരിഗണിക്കാം.

ഇനി കടുപ്പം ഉള്ള ഒരു ചായ വേണമെങ്കില്‍ അയാളോട് ഒരു ചായ കടുപ്പത്തില്‍ എന്ന് പറഞ്ഞാല്‍ മതി. അതുപോലെ ചായ മധുരം കുറച്ചു എന്ന് പറഞ്ഞാല്‍ മധുരം കുറഞ്ഞ ചായ കിട്ടും. ഇപ്പോള്‍ എന്തായി? ഫങ്ഷന്‍ ആയ ചായ ഉണ്ടാക്കല്‍ എന്നാ പ്രക്രിയയുടെ സ്വഭാവം കുറച്ചു മാറ്റി. അതിനു നമ്മള്‍ കടുപ്പം അല്ലെങ്കില്‍ മധുരം തുടങ്ങിയ പരാമെറ്ററുകള്‍ അത് പ്രാവര്‍ത്തികമാക്കുന്നതിനു മുന്പ് അത് പ്രവര്‍ത്തിപ്പിക്കുന്ന ആളോട് പറഞ്ഞു. അപ്പോള്‍ ആ ഫങ്ഷന്‍റെ പ്രവര്‍ത്തന രീതി കുറച്ചു മാറി നമുക്ക് വേണ്ട ചായ കിട്ടി.

<കോഡ്> turnLeft(howmanyTimes)

#വിവിധ തരം ഫങ്ഷനുകള്‍

രണ്ടു തരത്തിലുള്ള ഫങ്ഷനുകള്‍ ഉണ്ട്. ഒന്ന് നമ്മള്‍ പ്രോഗ്രാം എഴുതുന്നവര്‍ ഉണ്ടാക്കുന്നതും, അടുത്തത് പ്രോഗ്രാമ്മിംഗ്  ഭാഷയില്‍ മുന്‍കൂട്ടി ഉള്ളതും.

##യൂസര്‍ ഫങ്ഷന്‍

ഇതാണ് മുകളില്‍ കൊടുത്തിട്ടുള്ള ജാവാസ്ക്രിപ്റ്റ് പ്രോഗ്രാം എഴുതുന്ന യൂസര്‍ ആകുന്ന നമ്മള്‍ ഉണ്ടാക്കുന്ന ഫങ്ഷനുകള്‍. ഇങ്ങനെ നമ്മള്‍ ഉണ്ടാക്കിയ ഫങ്ഷനുകള്‍ക്കും പരാമെറ്ററുകള്‍ എടുക്കാം. 

<image> യുസര്‍ ഫങ്ഷന്‍ + പരാമെറ്റര്‍

##സിസ്റ്റം ഫങ്ങ്ഷന്‍

ഈ ഫങ്ഷനുകള്‍ നമുക്ക് വിളിക്കാന്‍ ആയി ഭാഷയില്‍ തന്നെ ഉള്ളതാണ്. കമ്പ്യൂട്ടര്‍ നമുക്ക് വേണ്ടി സ്വന്തമായി കണ്ടു പിടിച്ചതൊന്നും അല്ല മുന്‍കൂട്ടി അവിടെയുണ്ട് എന്ന് പറയുമ്പോള്‍. അത് ആ ഭാഷയിലുള്ള പ്രോഗ്രാം പ്രവര്‍ത്തിപ്പിക്കാന്‍ വേണ്ട പ്രോഗ്രാം അതായത് ജാവാസ്ക്രിപ്റ്റ് എടുത്താല്‍ബ്രൌസര്‍ ഉണ്ടാക്കിയ  പ്രോഗ്രാം എഴുത്തുകാര്‍ എഴുതി വച്ചിരിക്കുന്നതാണ്. മുന്‍പേ പറഞ്ഞപോലെ കമ്പ്യൂട്ടര്‍ സ്വന്തമായി ചിന്താശേഷി ഇല്ലാത്ത ഒരു യന്ത്രം മാത്രമാണ്.

<image> system ഫങ്ഷന്‍