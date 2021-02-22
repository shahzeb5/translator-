# translator-
A google translator madeup with the help of python libraries
 
from googletrans import Translator 
translater = Translator()

out=translater.translate("How are you", dest="de")
print(out.text)
