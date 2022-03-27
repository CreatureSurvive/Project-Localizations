# Project-Localizations
This is a dedicated repo for all my iOS project localizations

## How can I translate?
It is very simple:
- Fork or download this repo
- Choose the tweak(s) you want to localize
- If your language is already localized
    - You can edit the `*.strings` files to improve the localizations
- If your language is not localized
    - Copy the `base.lproj` folder for the tweak(s)
    - Rename the folder with your language's ISO-639-1 Code (Check tables below for supported language codes. [non-regional languages](#non_regional_languages), [regional languages](#regional_languages))
    - Translate each file by changing the text after each `=`
    - Pay attention to special characters such as `\(character), %(character), etc` these need to remain unchanged to ensure formatting works correctly. (Check [special format specifiers](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/Strings/Articles/formatSpecifiers.html) for a complete list)
- Make a Pull Request with your localizations, or send them to me at [support@creaturecoding.com](mailto:support@creaturecoding.com?subject=Localizations%20(PROJECT_NAME))
- If you would like credit attribution for your contribution, please include the name and (optional) contact link you would like to be credited with in your email or pull request comment

Thank you!

**NOTE: Some languages and regions may not be available on all versions of iOS. It is recommended that you test the localization before submitting.**

<a name="non_regional_languages"></a>
# Non-Regional Languages

| **Non-Regional Language** | **ISO-639-1 Code** | **lproj Name** |
|---|---|---|
| Afar | aa | aa.lproj |
| Abkhazian | ab | ab.lproj |
| Afrikaans | af | af.lproj |
| Amharic | am | am.lproj |
| Arabic | ar | ar.lproj |
| Assamese | as | as.lproj |
| Aymara | ay | ay.lproj |
| Azeri | az | az.lproj |
| Bashkir | ba | ba.lproj |
| Belarusian | be | be.lproj |
| Bulgarian | bg | bg.lproj |
| Bihari | bh | bh.lproj |
| Bislama | bi | bi.lproj |
| Bengali | bn | bn.lproj |
| Tibetan | bo | bo.lproj |
| Breton | br | br.lproj |
| Catalan | ca | ca.lproj |
| Corsican | co | co.lproj |
| Czech | cs | cs.lproj |
| Welsh | cy | cy.lproj |
| Danish | da | da.lproj |
| German | de | de.lproj |
| Divehi | div | div.lproj |
| Bhutani | dz | dz.lproj |
| Greek | el | el.lproj |
| English | en | en.lproj |
| Esperanto | eo | eo.lproj |
| Spanish | es | es.lproj |
| Estonian | et | et.lproj |
| Basque | eu | eu.lproj |
| Farsi | fa | fa.lproj |
| Finnish | fi | fi.lproj |
| Fiji | fj | fj.lproj |
| Faeroese | fo | fo.lproj |
| French | fr | fr.lproj |
| Frisian | fy | fy.lproj |
| Irish | ga | ga.lproj |
| Gaelic | gd | gd.lproj |
| Galician | gl | gl.lproj |
| Guarani | gn | gn.lproj |
| Gujarati | gu | gu.lproj |
| Hausa | ha | ha.lproj |
| Hebrew | he | he.lproj |
| Hindi | hi | hi.lproj |
| Croatian | hr | hr.lproj |
| Hungarian | hu | hu.lproj |
| Armenian | hy | hy.lproj |
| Interlingua | ia | ia.lproj |
| Indonesian | id | id.lproj |
| Interlingue | ie | ie.lproj |
| Inupiak | ik | ik.lproj |
| Indonesian | in | in.lproj |
| Icelandic | is | is.lproj |
| Italian | it | it.lproj |
| Hebrew | iw | iw.lproj |
| Japanese | ja | ja.lproj |
| Yiddish | ji | ji.lproj |
| Javanese | jw | jw.lproj |
| Georgian | ka | ka.lproj |
| Kazakh | kk | kk.lproj |
| Greenlandic | kl | kl.lproj |
| Cambodian | km | km.lproj |
| Kannada | kn | kn.lproj |
| Korean | ko | ko.lproj |
| Konkani | kok | kok.lproj |
| Kashmiri | ks | ks.lproj |
| Kurdish | ku | ku.lproj |
| Kirghiz | ky | ky.lproj |
| Kyrgyz | kz | kz.lproj |
| Latin | la | la.lproj |
| Lingala | ln | ln.lproj |
| Laothian | lo | lo.lproj |
| Slovenian | ls | ls.lproj |
| Lithuanian | lt | lt.lproj |
| Latvian | lv | lv.lproj |
| Malagasy | mg | mg.lproj |
| Maori | mi | mi.lproj |
| FYRO Macedonian | mk | mk.lproj |
| Malayalam | ml | ml.lproj |
| Mongolian | mn | mn.lproj |
| Moldavian | mo | mo.lproj |
| Marathi | mr | mr.lproj |
| Malay | ms | ms.lproj |
| Maltese | mt | mt.lproj |
| Burmese | my | my.lproj |
| Nauru | na | na.lproj |
| Nepali (India) | ne | ne.lproj |
| Dutch | nl | nl.lproj |
| Norwegian (Bokmal) | no | no.lproj |
| Occitan | oc | oc.lproj |
| (Afan)/Oromoor/Oriya | om | om.lproj |
| Oriya | or | or.lproj |
| Punjabi | pa | pa.lproj |
| Polish | pl | pl.lproj |
| Pashto/Pushto | ps | ps.lproj |
| Portuguese | pt | pt.lproj |
| Quechua | qu | qu.lproj |
| Rhaeto-Romanic | rm | rm.lproj |
| Kirundi | rn | rn.lproj |
| Romanian | ro | ro.lproj |
| Russian | ru | ru.lproj |
| Kinyarwanda | rw | rw.lproj |
| Sanskrit | sa | sa.lproj |
| Sorbian | sb | sb.lproj |
| Sindhi | sd | sd.lproj |
| Sangro | sg | sg.lproj |
| Serbo-Croatian | sh | sh.lproj |
| Singhalese | si | si.lproj |
| Slovak | sk | sk.lproj |
| Slovenian | sl | sl.lproj |
| Samoan | sm | sm.lproj |
| Shona | sn | sn.lproj |
| Somali | so | so.lproj |
| Albanian | sq | sq.lproj |
| Serbian | sr | sr.lproj |
| Siswati | ss | ss.lproj |
| Sesotho | st | st.lproj |
| Sundanese | su | su.lproj |
| Swedish | sv | sv.lproj |
| Swahili | sw | sw.lproj |
| Sutu | sx | sx.lproj |
| Syriac | syr | syr.lproj |
| Tamil | ta | ta.lproj |
| Telugu | te | te.lproj |
| Tajik | tg | tg.lproj |
| Thai | th | th.lproj |
| Tigrinya | ti | ti.lproj |
| Turkmen | tk | tk.lproj |
| Tagalog | tl | tl.lproj |
| Tswana | tn | tn.lproj |
| Tonga | to | to.lproj |
| Turkish | tr | tr.lproj |
| Tsonga | ts | ts.lproj |
| Tatar | tt | tt.lproj |
| Twi | tw | tw.lproj |
| Ukrainian | uk | uk.lproj |
| Urdu | ur | ur.lproj |
| English | us | us.lproj |
| Uzbek | uz | uz.lproj |
| Vietnamese | vi | vi.lproj |
| Volapuk | vo | vo.lproj |
| Wolof | wo | wo.lproj |
| Xhosa | xh | xh.lproj |
| Yiddish | yi | yi.lproj |
| Yoruba | yo | yo.lproj |
| Chinese | zh | zh.lproj |
| Zulu | zu | zu.lproj |

<a name="regional_languages"></a>
# Regional Languages

| **Regional Language** | **ISO-639-1 Code** | **lproj Name** |
|---|---|---|
| Arabic (U.A.E.) | ar-ae | ar_AE.lproj |
| Arabic (Bahrain) | ar-bh | ar_BH.lproj |
| Arabic (Algeria) | ar-dz | ar_DZ.lproj |
| Arabic (Egypt) | ar-eg | ar_EG.lproj |
| Arabic (Iraq) | ar-iq | ar_IQ.lproj |
| Arabic (Jordan) | ar-jo | ar_JO.lproj |
| Arabic (Kuwait) | ar-kw | ar_KW.lproj |
| Arabic (Lebanon) | ar-lb | ar_LB.lproj |
| Arabic (libya) | ar-ly | ar_LY.lproj |
| Arabic (Morocco) | ar-ma | ar_MA.lproj |
| Arabic (Oman) | ar-om | ar_OM.lproj |
| Arabic (Qatar) | ar-qa | ar_QA.lproj |
| Arabic (Saudi Arabia) | ar-SA | ar_sa.lproj |
| Arabic (Syria) | ar-sy | ar_SY.lproj |
| Arabic (Tunisia) | ar-tn | ar_TN.lproj |
| Arabic (Yemen) | ar-ye | ar_YE.lproj |
| German (Austria) | de-at | de_AT.lproj |
| German (Switzerland) | de-ch | de_CH.lproj |
| German (Liechtenstein) | de-li | de_LI.lproj |
| German (Luxembourg) | de-lu | de_LU.lproj |
| English (Australia) | en-au | en_AU.lproj |
| English (Belize) | en-bz | en_BZ.lproj |
| English (Canada) | en-ca | en_CA.lproj |
| English (United Kingdom) | en-gb | en_GB.lproj |
| English (Ireland) | en-ie | en_IE.lproj |
| English (Jamaica) | en-jm | en_JM.lproj |
| English (New Zealand) | en-nz | en_NZ.lproj |
| English (Philippines) | en-ph | en_PH.lproj |
| English (Trinidad) | en-tt | en_TT.lproj |
| English (United States) | en-us | en_US.lproj |
| English (South Africa) | en-za | en_ZA.lproj |
| English (Zimbabwe) | en-zw | en_ZW.lproj |
| Spanish (Argentina) | es-ar | es_AR.lproj |
| Spanish (Bolivia) | es-bo | es_BO.lproj |
| Spanish (Chile) | es-cl | es_CL.lproj |
| Spanish (Colombia) | es-co | es_CO.lproj |
| Spanish (Costa Rica) | es-cr | es_CR.lproj |
| Spanish (Dominican Republic) | es-do | es_DO.lproj |
| Spanish (Ecuador) | es-ec | es_EC.lproj |
| Spanish (España) | es-es | es_ES.lproj |
| Spanish (Guatemala) | es-gt | es_GT.lproj |
| Spanish (Honduras) | es-hn | es_HN.lproj |
| Spanish (Mexico) | es-mx | es_MX.lproj |
| Spanish (Nicaragua) | es-ni | es_NI.lproj |
| Spanish (Panama) | es-pa | es_PA.lproj |
| Spanish (Peru) | es-pe | es_PE.lproj |
| Spanish (Puerto Rico) | es-pr | es_PR.lproj |
| Spanish (Paraguay) | es-py | es_PY.lproj |
| Spanish (El Salvador) | es-sv | es_SV.lproj |
| Spanish (United States) | es-us | es_US.lproj |
| Spanish (Uruguay) | es-uy | es_UY.lproj |
| Spanish (Venezuela) | es-ve | es_VE.lproj |
| French (Belgium) | fr-be | fr_BE.lproj |
| French (Canada) | fr-ca | fr_CA.lproj |
| French (Switzerland) | fr-ch | fr_CH.lproj |
| French (Luxembourg) | fr-lu | fr_LU.lproj |
| French (Monaco) | fr-mc | fr_MC.lproj |
| Italian (Switzerland) | it-ch | it_CH.lproj |
| Norwegian (Bokmal) | nb-no | nb_NO.lproj |
| Dutch (Belgium) | nl-be | nl_BE.lproj |
| Norwegian | nn-no | nn_NO.lproj |
| Portuguese (Brazil) | pt-br | pt_BR.lproj |
| Romanian (Moldova) | ro-md | ro_MD.lproj |
| Russian (Moldova) | ru-md | ru_MD.lproj |
| Swedish (Finland) | sv-fi | sv_FI.lproj |
| Chinese (China) | zh-cn | zh_CN.lproj |
| Chinese (Hong Kong SAR) | zh-hk | zh_HK.lproj |
| Chinese (Macau SAR) | zh-mo | zh_MO.lproj |
| Chinese (Singapore) | zh-sg | zh_SG.lproj |
| Chinese (Taiwan) | zh-tw | zh_TW.lproj |
