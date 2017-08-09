# classDesc
# stack 
Stack eslinde bir temporary olan computerin RAM memorysinin bir hissesidir.
Hansisa bir variable declare olunanda o variable temporarily yuklenir stack-a , lakin bu funksiya exit olunanda butun ona mexsus variable-lar freed olunir (yeni delete olunur).Stack-a butun variable-lar FILO (first in,last out) qaydasi ile yazilib pozulur: birinci yazilan variable axirinci pozulur ve vice versa.Stack relatively daha bir stable memory sayilir.

# heap
Heap Stack kimi user-le hele de yaxindan control olunmur ve user ona hemise secondary yolla reference eliye biler. C dilinden emele gelen bezi funksiyalar buna da komek eliye biler, such as callog() ve s. Heap-da yazilan variblar stack-a referencce eliye bilerler, mesele ucun bir array-in daxilinde olan variabllar stack-a baib oradan bir value goture bilerler.Stack-a nisbeten Heap daha dynamic bir part of memory-dir.

# value type
Eslinde Stack-da yazilan variable-lar value data type sayilir . Value typelar temporarydir, onlarin qiymetleri deyise biler, ve variable-larin ozu de delete oluna biler

# Reference type
Reference type olanlar ise obyektin ozunu yox amma stack-da yerlesen variable-lardan bir refernce alirlar.Mesele ucun 
HEAP
var array = [a,b,c]; // arrayin icinde olan variablelar stack-a reference eliyirler
STACK
var a = 5; // stack-da yerlesen variablar temporary olmaglarina baxmayaraq HEAP-deki array-a reference verir
var b = 7;
var c = 1;

# Class
Class eslinde obyekt ve ya obyektlerin bir qelibi sayilir. Biz classlari obyekt yaradanda constructor kimi istifade ede bilerik. Bundan elave classlar bir nece obyektin common property ve characteristics -lerini saxliya bilir.

# Object
Obyekt eslinde Classlin bir instance-i sayilir. Objectin abstract (yeni ozune mexsus) ve eyni vaxtda onun qeilibi ile common property ve characteristicsleri ola biler

