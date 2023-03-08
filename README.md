# PackagesOfT24ExcelFile

--------------------------------------------------------------------------------------------------------------------------------------
                                                      packages details
                                                      
 agar huma package uthana hai aik jaga sa dosri jaga laka jana hai to na kia karonga phala us menu ka number jasa forexample ?254 hai ![image](https://user-images.githubusercontent.com/40827670/223681035-ef34afa2-3f43-486c-bece-f794c5376aa1.png)
 usko ma HMM (helpText MainMenu) ma search karonga ![image](https://user-images.githubusercontent.com/40827670/223681234-406e8e34-fe07-49e2-819f-0f1265052989.png)
to search karna ka bad waha pa jo name show ho rahe honga wo bhi ae ga or uski id bhi ae gi or uski id jo ae gi usko ma HM(helptext menu) ma searhc karonga kio ka hamsaha main menu ma main id hoti hai baqi ki tamam id HM ma hoti hai uska andar matlab ab ma agar uska andar bhi koi or HM chaeya to ma uski jo name show ho rahe honga to ma uska name copy karka phir HM ma search karonga to ajae ga 
![image](https://user-images.githubusercontent.com/40827670/223682245-934a8547-8d1b-4aa3-a725-c51a3973a3fd.png)


ab mujha agar koi HM jasa teller ka cheheya to ma kia karonga ak login karonga tRun EX sa us env pa or phir ma wo routine ka name MENU.PROCESSOR likha ka enter karonga to phir ma uska HM menu ka name donga jasa Teller to usko enter karonga to wo aik file bna daga %commo.. wala path pa or phir us file ko agar mujha ya bhi cheya ka ya core ki hai ya core ki ni hai us ma kuch records to ma uska lia FoundNotFound ki routine PKMB.READ.SL.b chalo ga isi tarha usko chalana ka tarika FoundNotFoundHELP.FILE.txt is file ma hai or ya routine model bank local pa chaalaa gi ya env pa bhi chala sakta ha chalana ka bad phir wo 2 files bana ka daga found ki and not found ki
                                                  
                                                 ya english ma thora hai dakha lo  how we can extract complete package from others environment
 1: first we run routine that routine work to extract HM helptext menu
          we have 2 routines but we execute one only MENU.PROCESSOR it will call second one own  MENU.EXTRACTOR
 2: when it execute succesfuly it create a file in &como... if this file is not be there we can copy all record from classic mode when we execute MENU.PROCESSOR all             record showing in classic mode too.
 3: first we put insert file on the environment 
first we execute HM helpText menu routine and get all record from there and in that record 
we put in this excel file or maintaine it and in that file we wrote opposite rename of that field name those we change our prefix
this file is a sample of PKMB Trade Factory.xlsx this

![image](https://user-images.githubusercontent.com/40827670/218038652-cb121a41-8d05-4b0a-a3d4-756d88e05d8a.png)


-----------------------------------------------------------------------------------------------------------------------------------------------
                                                routine details how we can manage in excel file
                                                
![image](https://user-images.githubusercontent.com/40827670/218040438-8a2802dc-6bf6-4e61-b073-5dafae0ebcd0.png)
