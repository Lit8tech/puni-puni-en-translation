# Yo-Kai Watch Puni Puni English Translation 

An English translation for the popular Japanese mobile game, Yo-kai Watch Puni Puni.


Created by:

Lit8tech (Creator, former lead android developer, wibble wobble text porter, lead iOS developer)

Woganog (Lead android developer, wibble wobble asset porter)

Hasslehoncho (text translator)

Math-kk (Image translator)

Shuri-ken (left, former text translator)

Split-PS-Soup (left, former text translator)

101Leafy (left, former text translator)

(N67 (fired, former "text translator")






# Installation Instructions for CMD-IOS version:

Simply open a terminal app on your jailbroken idevice or use ssh and type this command (also make sure that you have root privileges):

rm -r /var/mobile/Containers/Data/Application/7F760EBB-DE5B-4F38-A138-279EF81201AC/Library/Caches/movie && rm -r /var/mobile/Containers/Data/Application/7F760EBB-DE5B-4F38-A138-279EF81201AC/Library/Caches/image && rm -r /var/mobile/Containers/Data/Application/7F760EBB-DE5B-4F38-A138-279EF81201AC/Library/Caches/skill && rm -r /var/mobile/Containers/Data/Application/7F760EBB-DE5B-4F38-A138-279EF81201AC/Library/Caches/ywp_cud && rm -r /var/containers/Bundle/Application/6A9B3616-2B61-4E7A-8C6D-54B539F53217/YWP.app/AppLovinSDKResources.bundle && rm -r /var/containers/Bundle/Application/6A9B3616-2B61-4E7A-8C6D-54B539F53217/YWP.app/PAGAdSDK.bundle && rm -r /var/containers/Bundle/Application/6A9B3616-2B61-4E7A-8C6D-54B539F53217/YWP.app/image && rm -r /var/containers/Bundle/Application/6A9B3616-2B61-4E7A-8C6D-54B539F53217/YWP.app/localize && rm -r /var/containers/Bundle/Application/6A9B3616-2B61-4E7A-8C6D-54B539F53217/YWP.app/movie && rm -r /var/containers/Bundle/Application/6A9B3616-2B61-4E7A-8C6D-54B539F53217/YWP.app/sound && rm -r /var/containers/Bundle/Application/6A9B3616-2B61-4E7A-8C6D-54B539F53217/YWP.app/youkai && git clone https://github.com/Lit8tech/puni-puni-EN-translation.git && cd puni-puni-EN-translation && mv movie /var/mobile/Containers/Data/Application/7F760EBB-DE5B-4F38-A138-279EF81201AC/Library/Caches && mv image /var/mobile/Containers/Data/Application/7F760EBB-DE5B-4F38-A138-279EF81201AC/Library/Caches && mv skill /var/mobile/Containers/Data/Application/7F760EBB-DE5B-4F38-A138-279EF81201AC/Library/Caches && mv ywp_cud /var/mobile/Containers/Data/Application/7F760EBB-DE5B-4F38-A138-279EF81201AC/Library/Caches && cd YWP.app && mv AppLovinSDKResources.bundle /var/containers/Bundle/Application/6A9B3616-2B61-4E7A-8C6D-54B539F53217/YWP.app && mv PAGAdSDK.bundle /var/containers/Bundle/Application/6A9B3616-2B61-4E7A-8C6D-54B539F53217/YWP.app && mv image /var/containers/Bundle/Application/6A9B3616-2B61-4E7A-8C6D-54B539F53217/YWP.app && mv localize /var/containers/Bundle/Application/6A9B3616-2B61-4E7A-8C6D-54B539F53217/YWP.app && mv movie /var/containers/Bundle/Application/6A9B3616-2B61-4E7A-8C6D-54B539F53217/YWP.app && mv sound /var/containers/Bundle/Application/6A9B3616-2B61-4E7A-8C6D-54B539F53217/YWP.app && mv youkai /var/containers/Bundle/Application/6A9B3616-2B61-4E7A-8C6D-54B539F53217/YWP.app

# Android root installation instructions:

1) Code -> Download ZIP and extract it.
3) Dowload apk editor, open it then click on "Select Apk from App" and select Puni Puni, then press on the files tab and replace all the folders with the same names as the ones in YWP.app from the github repo, build the app and install.
4) Go to root directory, then `data_mirror/data_ce/null/0/com.Level5.YWP/files`.
5) Replace the folders and files in the game directory with the counterparts from the link.
*Note: Replace ywp_cud at your own risk! It can lead to crashes and bugs very easily.*
5) Enjoy!

# FaQ:

What other languages are you translating into?:

So these are the languages we are translating into
English, French, German, Spanish also after English translation is fully done Russian and Ukrainian 
But rn we are practically only focusing on English, we just have people already translating bits and pieces in the other languages, but since there is no known dump of the other languages download files as of know, so even when we start fully working on those translations, it will take way longer to complete than the English one.

What tools are you using to open puni's files?:

Pngs and .strings (which is a type of text file) are  universal file types and not level 5 or NHN specific and most of the other files we don’t need to edit,except cud files (which are text files).
We know .cud files are possible to edit but no one will tell us because they can also be used for cheating as they also contain settings that you can edit for cheating purposes.
We can also transfer cuds from wibwob but those are missing strings compared to the puni ones since puni is newer and and some break the game.
So technically we don't need any specific software except the either non-existent or just hidden/secret .cud decrypting software. So any knowledge on how to decrypt cuds would be greatly appreciated.
