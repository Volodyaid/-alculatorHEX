# Hex Calculator (0-9A-F)
This calculator is a continuation of the previous program,   
designed for the most part for sequential generation   
of numbers in hex format, used as entropy to obtain 
consecutive keywords.   
   
Only in this version there is already a full-fledged calculator,   
with which you can quickly perform calculations      
(addition, subtraction, multiplication, division) of two numbers.   
add // Addition   
sub // Subtraction   
mul // Multiplication   
div // Division   

Calculations are performed modulo:   
115792089237316195423570985008687907852837564279074904382605163141518161494337   

The calculator works on Linux   

Launch example:   
./HexCalculator 48797201165521252720151571441291384041 mul 1000 output.txt 19291804893079641364924223074   
where   
48797201165521252720151571441291384041 is the first initial number   
mul - multiplication   
output.txt - a file for recording the results of calculations   
1000 - how many times should each received number be multiplied by the second initial number   
19291804893079641364924223074 is the second initial number   

The program writes the obtained values in HEX format to a file,   
here are the first 10 lines in the file obtained as a result of calculations:   

1b41f5f6dd4be80a0e0c69af4719ea4cd12345c5e6da51d725177f32   
50731bb2891faa3573babbe3aee554fba88b0e8fbd4f1c7fbba59cfb36289d56   
8056d99f3854fbe1021cfec75e33bffe0fdba3924e1b7a7bd23b4d7ed10651df   
533ba529e8852710b3a09c94fe6e0266e1d287e426958a3a51ca8257a69a1edc   
14e7b85b8a12396c09c71d13cdd67eedcdcbbeb5dbea11463b6bceb6c1bc6e18   
a92d000dfaa8ae490f48851a50058e49a3cc6c459f656a398335bac67bbfbc89   
56a8dcc9aa79955f11ede59915b315185c01bc167b0a888e3fba42613b0b1f30   
cabe8a5fd08500133027c680b487053c53ef2068838e5463a44f70d1f8abc4a7   
5f186c16327bfff5e54143eb39f35c5d4c537f502906d01f8bf013c99fe4f35d   
4ab34387c7748588b181c62e4c0d53f21371ba5e7010e3ebf94a886bae8a84b7   
.............................................................   
Данный калькулятор является продолжением предыдущей программы,   
предназначенной по большей части для последовательной генерации   
чисел в hex формате, используемых как энтропии для получения   
последовательных сид фраз.   

Только в этой версии представлен уже полноценный калькулятор,   
с помощью которого вы сможете быстро произвести вычисления    
(сложение, вычитание, умножение, деление) двух чисел.   
add // Сложение   
sub // Вычитание   
mul // Умножение   
div // Деление   

Вычисления производятся по модулю:   
115792089237316195423570985008687907852837564279074904382605163141518161494337   

Калькулятор работает в Linux   

Пример запуска:   
./HexCalculator 48797201165521252720151571441291384041 mul 1000 output.txt 19291804893079641364924223074   
где   
48797201165521252720151571441291384041 - первое исходное число   
mul - умножение   
output.txt - файл для записи результатов вычислений   
1000 - сколько раз каждое полученное число умножать на второе исходное число число   
19291804893079641364924223074 - второе исходное число   

Программа полученные значения записывает в HEX формате в файл,   
вот первые 10 строк в файла, полученные в результате вычислений:   

1b41f5f6dd4be80a0e0c69af4719ea4cd12345c5e6da51d725177f32   
50731bb2891faa3573babbe3aee554fba88b0e8fbd4f1c7fbba59cfb36289d56   
8056d99f3854fbe1021cfec75e33bffe0fdba3924e1b7a7bd23b4d7ed10651df   
533ba529e8852710b3a09c94fe6e0266e1d287e426958a3a51ca8257a69a1edc   
14e7b85b8a12396c09c71d13cdd67eedcdcbbeb5dbea11463b6bceb6c1bc6e18   
a92d000dfaa8ae490f48851a50058e49a3cc6c459f656a398335bac67bbfbc89   
56a8dcc9aa79955f11ede59915b315185c01bc167b0a888e3fba42613b0b1f30   
cabe8a5fd08500133027c680b487053c53ef2068838e5463a44f70d1f8abc4a7   
5f186c16327bfff5e54143eb39f35c5d4c537f502906d01f8bf013c99fe4f35d   
4ab34387c7748588b181c62e4c0d53f21371ba5e7010e3ebf94a886bae8a84b7   
