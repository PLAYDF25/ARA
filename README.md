 gg.toast("https://t.me/ARA_HACK")
HOME=1
function HOME()
HM = gg.choice({'[BYPASS]','[FUNCTIONS]','[LANG/ЯЗЫК]','[CHANGES]','[EXIT]'}, nil,' ▰ ▱ ARA HACK ▰ ▱ \n    PUBG: 0.7.0  ▎SCRIPT v 3.3\n            MADE BY 𒈞PLAYDF25\n                          https://t.me/ARA_HACK')
if HM == 1 then BYPASS() end
if HM == 2 then FUNCTIONS() end
if HM == 3 then LANG() end
if HM == 4 then NEWS() end
if HM == 5 then EXIT() end 
HOMEDM=-1
end
function LANG()
LG = gg.choice({'[1] ENGLISH','[2] РУССКИЙ','[BACK]'},nil,'Choose your language\nВыбери свой язык')
if LG == 1 then HOME() end
if LG == 2 then RUS() end
if LG == 3 then HOME() end
end
function FUNCTIONS()
GM = gg.multiChoice({'[1] Recoil Menu','[2] Magic Bullet Menu','[3] WallHack Menu','[4] Colors Menu','[5] AimBot Menu','[6] Antenna Menu','[7] No Objects Menu','[8] UAZ Menu','[9] Firing Rate Menu','[10] Player Model Menu','[11] Lift Menu','[12] Zoom Menu','[13] Jump Menu','[14] Menu Other Functions','[BACK]'},nil,'Functions Menu')
if GM == nil then

else
if GM[1] == true then RMMG() end
if GM[2] == true then MBMM() end 
if GM[3] == true then WHMM() end

if GM[4] == true then CMEN() end
if GM[5] == true then AIMMENU() end
if GM[6] == true then ANNMENU() end
if GM[7] == true then NOOBJM() end
if GM[8] == true then UAZMENUU() end
if GM[9] == true then MENURATE() end
if GM[10] == true then PMODELM() end
if GM[11] == true then LIFTMENU() end
if GM[12] == true then ZOOMXMENU() end
if GM[13] == true then JUMPMENU() end
if GM[14] == true then OOOFUNC() end
if GM[15] == true then HOME() end 
end

end
function OOOFUNC()
OOOF = gg.multiChoice({"[1] Micro SpeedHack","[2] Extended Review","[3] Drive Through Wall","[4] Kar98k Powershot","[5] Quick Weapon Switch","[6] Fly Buggies","[BACK]"}, nil, 'Menu Other Functions')
if OOOF == nil then

else
if OOOF[1] == true then MISH() end
if OOOF[2] == true then VXX() end
if OOOF[3] == true then DTW() end
if OOOF[4] == true then KP() end
if OOOF[5] == true then QWS() end
if OOOF[6] == true then FLYB() end
if OOOF[7] == true then FUNCTIONS() end 
end
end
function AIMMENU()
AIMM = gg.multiChoice({"[1] Micro AimBot","[2] Medium AimBot","[3] Ultra AimBot","[4] Auto HeadShot","[BACK]"}, nil, 'AimBot Menu USE IN LOBBY/GAME')
if AIMM == nil then

else
if AIMM[1] == true then MICR() end
if AIMM[2] == true then MED() end
if AIMM[3] == true then UAI() end
if AIMM[4] == true then AUTOHS() end
if AIMM[5] == true then FUNCTIONS() end 
end
end
function JUMPMENU()
JUMPP = gg.multiChoice({"[1] Long Jump","[2] High Jump","[3] Multi Jump","[BACK]"}, nil, 'Jump Menu USE IN GAME')
if JUMPP == nil then

else
if JUMPP[1] == true then LLJ() end
if JUMPP[2] == true then HJJJ() end
if JUMPP[3] == true then MULTJUMP() end
if JUMPP[4] == true then FUNCTIONS() end 
end
end
function ZOOMXMENU()
ZOOMX = gg.multiChoice({"[1] Zoom X4","[2] Zoom X8","[3] Zoom X15","[BACK]"}, nil, 'Zoom Menu USE IN GAME')
if ZOOMX == nil then

else
if ZOOMX[1] == true then Z4X() end
if ZOOMX[2] == true then Z8X() end
if ZOOMX[3] == true then Z15X() end
if ZOOMX[4] == true then FUNCTIONS() end 
end
end
function LIFTMENU()
LIFTT = gg.multiChoice({"[1] Lift Sit Down Aim","[2] Lift Sit","[BACK]"}, nil, 'Lift Menu USE IN GAME')
if LIFTT == nil then

else
if LIFTT[1] == true then LSDA() end
if LIFTT[2] == true then LIFTW() end
if LIFTT[3] == true then FUNCTIONS() end 
end
end
function PMODELM()
PMG = gg.multiChoice({"[1] Player Model Big","[2] Player Model Small","[BACK]"}, nil, 'Player Model Menu USE IN GAME')
if PMG == nil then

else
if PMG[1] == true then BIG() end
if PMG[2] == true then SMALL() end
if PMG[3] == true then FUNCTIONS() end 
end
end
function MENURATE()
RATE = gg.multiChoice({"[1] Firing Rate M4","[2] Firing Rate SC","[3] Firing Rate AK","[BACK]"}, nil, 'Firing Rate Menu USE IN GAME')
if RATE == nil then

else
if RATE[1] == true then M4() end
if RATE[2] == true then SCAR() end
if RATE[3] == true then AK47() end
if RATE[4] == true then FUNCTIONS() end 
end
end
function UAZMENUU()
UAZZ = gg.multiChoice({"[1] Acceleration UAZ","[2] Underwater UAZ","[BACK]"}, nil, 'UAZ Menu USE IN GAME')
if UAZZ == nil then

else
if UAZZ[1] == true then AUA() end
if UAZZ[2] == true then UAZW() end
if UAZZ[3] == true then FUNCTIONS() end 
end
end
function NOOBJM()
NOBJ = gg.multiChoice({"[1] No Grass","[2] No Grass/Trees v1","[3] No Grass/Trees v2","[4] No Grass/Houses","[BACK]"}, nil, 'No Objects Menu USE IN GAME')
if NOBJ == nil then

else
if NOBJ[1] == true then GGG() end
if NOBJ[2] == true then SOGT() end
if NOBJ[3] == true then NOGT() end
if NOBJ[4] == true then NOHOUS() end
if NOBJ[5] == true then FUNCTIONS() end 
end
end
function ANNMENU()
ANNN = gg.multiChoice({"[1] Antenna Run Side v1","[2] Antenna Run Side v2","[3] Antenna Run Up","[4] Antenna Run Big","[5] Antenna Always v1","[6] Antenna Always v2","[7] Equipment Items Antenna","[BACK]"}, nil, 'Antenna Menu USE IN GAME')
if ANNN == nil then

else
if ANNN[1] == true then ANR1() end
if ANNN[2] == true then ANR3() end
if ANNN[3] == true then ANR2() end
if ANNN[4] == true then ANR4() end
if ANNN[5] == true then ANR6() end
if ANNN[6] == true then ANR7() end
if ANNN[7] == true then EIA() end
if ANNN[8] == true then FUNCTIONS() end 
end
end
function CMEN()
CMM = gg.multiChoice({"[1] Body Blue","[2] Body Green","[3] Body Red","[4] Body Pixel","[5] Body Pink","[6] Body Yellow","[7] Body White v1","[8] Body White v2","[9] Body Black v1","[10] Body Red HDR","[11] Body White v3","[12] Body Black v2","[13] Body Red v2","[14] Body Emerald","[15] Body RGB","[16] Body Crystal","[17] Body Gradient  v1","[18] Body Gradient v2","[19] Body Acid","[20] Snow Landscape","[21] Black Landspace","[22] Violet Vegetation","[23] Black Sky","[24] Clear Sky","[25] Body Crystal RGB","[BACK]"}, nil, 'Colors Menu USE IN GAME')
if CMM == nil then
else
if CMM[1] == true then CB() end 
if CMM[2] == true then CG() end
if CMM[3] == true then LRB() end
if CMM[4] == true then PBB() end
if CMM[5] == true then BBR() end
if CMM[6] == true then YEL() end
if CMM[7] == true then WHIT() end
if CMM[8] == true then WHIT2() end
if CMM[9] == true then BODYB() end
if CMM[10] == true then REDV2() end
if CMM[11] == true then WHIT3() end
if CMM[12] == true then BLACK() end
if CMM[13] == true then REDV3() end
if CMM[14] == true then EMLD() end
if CMM[15] == true then RGB() end
if CMM[16] == true then CL() end
if CMM[17] == true then GT() end
if CMM[18] == true then GT2() end
if CMM[19] == true then ACID() end
if CMM[20] == true then STT() end
if CMM[21] == true then BLS() end
if CMM[22] == true then VTT() end
if CMM[23] == true then BBS() end
if CMM[24] == true then CCS() end
if CMM[25] == true then CRGB() end
if CMM[26] == true then FUNCTIONS() end 
end
end
function RMMG()
RM = gg.multiChoice({"[1] Less Recoil","[2] No Recoil","[BACK]"}, nil, 'Recoil Menu USE IN LOBBY')
if RM == nil then

else
if RM[1] == true then LLR() end
if RM[2] == true then NOR() end
if RM[3] == true then FUNCTIONS() end 
end
end
function MBMM()
MB = gg.multiChoice({"[1] Magic Bullet v4","[2] Magic Bullet v5","[3] Magic Bullet v6","[BACK]"}, nil, 'Magic Bullet Menu USE IN GAME/LOBBY')
if MB == nil then

else
if MB[1] == true then MB11() end
if MB[2] == true then MB77() end
if MB[3] == true then MB666() end
if MB[4] == true then FUNCTIONS() end 
end
end
function WHMM()
WHH = gg.multiChoice({"[1] Player WallHack v1","[2] Player WallHack v2","[3] Player WallHack v3","[4] Item WallHack","[5] WallShot","[BACK]"}, nil, 'WallHack Menu USE IN GAME')
if WHH == nil then

else
if WHH[1] == true then PLAYER() end
if WHH[2] == true then snappp() end
if WHH[3] == true then PWHV3() end
if WHH[4] == true then ITEM() end
if WHH[5] == true then WALLS() end
if WHH[6] == true then FUNCTIONS() end 
end
end



function FUNCTIONSRUS()
GMR = gg.multiChoice({'[1] Меню Отдачи','[2] Меню Магической Пули','[3] Меню Взлома Сквозь Стены','[4] Меню Цветов','[5] Меню Автоматической Наводки','[6] Меню Антенны','[7] Меню Удаления Объектов','[8] Меню Уазика','[9] Меню Скорострельности','[10] Меню Модели Игрока','[11] Меню Подъёма','[12] Меню Увеличения Прицела','[13] Меню Прыжка','[14] Меню Других Функций','[НАЗАД]'},nil,'Меню Функций')
if GMR == nil then
else
if GMR[1] == true then RMMGR() end
if GMR[2] == true then MBMMR() end 
if GMR[3] == true then WHMMR() end
if GMR[4] == true then CMENR() end
if GMR[5] == true then AIMMENUR() end
if GMR[6] == true then ANNMENUR() end
if GMR[7] == true then NOOBJMR() end
if GMR[8] == true then UAZMENUUR() end
if GMR[9] == true then MENURATER() end
if GMR[10] == true then PMODELMR() end
if GMR[11] == true then LIFTMENUR() end
if GMR[12] == true then ZOOMXMENUR() end
if GMR[13] == true then JUMPMENUR() end
if GMR[14] == true then OOOFUNCR() end
if GMR[15] == true then RUS() end 
end
end
function OOOFUNCR()
OOOF = gg.multiChoice({"[1] Слабое Увеличение Скорости","[2] Расширенный Вид","[3] Ездить Сквозь Стены","[4] Kar98k Увеличенный Урон","[5] Быстрое Переключение Оружий","[6] Полет На Багги","[НАЗАД]"}, nil, 'Меню Других Функций')
if OOOF == nil then

else
if OOOF[1] == true then MISH() end
if OOOF[2] == true then VXX() end
if OOOF[3] == true then DTW() end
if OOOF[4] == true then KP() end
if OOOF[5] == true then QWS() end
if OOOF[6] == true then FLYB() end
if OOOF[7] == true then FUNCTIONSRUS() end 
end
end
function AIMMENUR()
AIMM = gg.multiChoice({"[1] Слабая Автоматическая Наводка","[2] Средняя Автоматическая Наводка","[3] Максимальная Автоматическая Наводка","[4] Автоматическое Попадание в Голову","[НАЗАД]"}, nil, 'Меню Автоматической Наводки ИСПОЛЬЗОВАТЬ В ЛОББИ/ИГРЕ')
if AIMM == nil then

else
if AIMM[1] == true then MICR() end
if AIMM[2] == true then MED() end
if AIMM[3] == true then UAI() end
if AIMM[4] == true then AUTOHS() end
if AIMM[5] == true then FUNCTIONSRUS() end 
end
end
function JUMPMENUR()
JUMPP = gg.multiChoice({"[1] Медленный Прыжок","[2] Высокий Прыжок","[3] Множественные Прыжки","[НАЗАД]"}, nil, 'Меню Прыжка ИСПОЛЬЗОВАТЬ В ИГРЕ')
if JUMPP == nil then

else
if JUMPP[1] == true then LLJ() end
if JUMPP[2] == true then HJJJ() end
if JUMPP[3] == true then MULTJUMP() end
if JUMPP[4] == true then FUNCTIONSRUS() end 
end
end
function ZOOMXMENUR()
ZOOMX = gg.multiChoice({"[1] Увеличение X4","[2] Увеличение X8","[3] Увеличение X15","[НАЗАД]"}, nil, 'Меню Увеличения Прицела ИСПОЛЬЗОВАТЬ В ИГРЕ')
if ZOOMX == nil then

else
if ZOOMX[1] == true then Z4X() end
if ZOOMX[2] == true then Z8X() end
if ZOOMX[3] == true then Z15X() end
if ZOOMX[4] == true then FUNCTIONSRUS() end 
end
end
function LIFTMENUR()
LIFTT = gg.multiChoice({"[1] Подъём Сидя Открыть Прицел","[2] Подъём Сидя","[НАЗАД]"}, nil, 'Меню Подъёма ИСПОЛЬЗОВАТЬ В ИГРЕ')
if LIFTT == nil then

else
if LIFTT[1] == true then LSDA() end
if LIFTT[2] == true then LIFTW() end
if LIFTT[3] == true then FUNCTIONSRUS() end 
end
end
function PMODELMR()
PMG = gg.multiChoice({"[1] Большая Модель Игрока","[2] Маленькая Модель Игрока","[НАЗАД]"}, nil, 'Меню Модели Игрока ИСПОЛЬЗОВАТЬ В ИГРЕ')
if PMG == nil then

else
if PMG[1] == true then BIG() end
if PMG[2] == true then SMALL() end
if PMG[3] == true then FUNCTIONSRUS() end 
end
end
function MENURATER()
RATE = gg.multiChoice({"[1] Скорострельность M4","[2] Скорострельность SC","[3] Скорострельность AK","[НАЗАД]"}, nil, 'Меню Скорострельности ИСПОЛЬЗОВАТЬ В ИГРЕ')
if RATE == nil then

else
if RATE[1] == true then M4() end
if RATE[2] == true then SCAR() end
if RATE[3] == true then AK47() end
if RATE[4] == true then FUNCTIONSRUS() end 
end
end
function UAZMENUUR()
UAZZ = gg.multiChoice({"[1] Ускорение Уазика","[2] Уазик-Подводная Лодка","[НАЗАД]"}, nil, 'Меню Уазика ИСПОЛЬЗОВАТЬ В ИГРЕ')
if UAZZ == nil then

else
if UAZZ[1] == true then AUA() end
if UAZZ[2] == true then UAZW() end
if UAZZ[3] == true then FUNCTIONSRUS() end 
end
end
function NOOBJMR()
NOBJ = gg.multiChoice({"[1] Убрать Траву","[2] Убрать Траву и Деревья v1","[3] Убрать Траву и Деревья v2","[4] Убрать Деревья и Дома","[НАЗАД]"}, nil, 'Меню Удаления Объектов ИСПОЛЬЗОВАТЬ В ИГРЕ')
if NOBJ == nil then

else
if NOBJ[1] == true then GGG() end
if NOBJ[2] == true then SOGT() end
if NOBJ[3] == true then NOGT() end
if NOBJ[4] == true then NOHOUS() end
if NOBJ[5] == true then FUNCTIONSRUS() end 
end
end
function ANNMENUR()
ANNN = gg.multiChoice({"[1] Антенна Из Бока При Беге v1","[2] Антенна Из Бока При Беге v2","[3] Антенна Из Головы При Беге","[4] Большая Антенна При Беге","[5] Постоянная Антенна v1","[6] Постоянная Антенна v2","[7] Антенна Экипировки","[НАЗАД]"}, nil, 'Меню Антенны ИСПОЛЬЗОВАТЬ В ИГРЕ')
if ANNN == nil then

else
if ANNN[1] == true then ANR1() end
if ANNN[2] == true then ANR3() end
if ANNN[3] == true then ANR2() end
if ANNN[4] == true then ANR4() end
if ANNN[5] == true then ANR6() end
if ANNN[6] == true then ANR7() end
if ANNN[7] == true then EIA() end
if ANNN[8] == true then FUNCTIONSRUS() end 
end
end
function CMENR()
CMM = gg.multiChoice({"[1] Голубое Тело","[2] Зелёное Тело","[3] Красное Тело","[4] Пиксельное Тело","[5] Розовое Тело","[6] Жёлтое Тело","[7] Белое Тело v1","[8] Белое Тело v2","[9] Чёрное Тело v1","[10] Красное Тело МАКСИМАЛЬНАЯ ГРАФИКА","[11] Белое Тело v3","[12] Чёрное Тело v2","[13] Красное Тело v2","[14] Изумрудное Тело","[15] RGB Тело","[16] Кристальное Тело","[17] Градиентовое Тело v1","[18] Градиентовое Тело v2","[19] Кислотное Тело","[20] Снежный Ландшафт","[21] Чёрный Ландшафт","[22] Фиолетовая Растительность","[23] Чёрное Небо","[24] Чистое Небо","[25] Кристальное RGB Тело","[НАЗАД]"}, nil, 'Меню Цветов ИСПОЛЬЗОВАТЬ В ИГРЕ')
if CMM == nil then

else
if CMM[1] == true then CB() end 
if CMM[2] == true then CG() end
if CMM[3] == true then LRB() end
if CMM[4] == true then PBB() end
if CMM[5] == true then BBR() end
if CMM[6] == true then YEL() end
if CMM[7] == true then WHIT() end
if CMM[8] == true then WHIT2() end
if CMM[9] == true then BODYB() end
if CMM[10] == true then REDV2() end
if CMM[11] == true then WHIT3() end
if CMM[12] == true then BLACK() end
if CMM[13] == true then REDV3() end
if CMM[14] == true then EMLD() end
if CMM[15] == true then RGB() end
if CMM[16] == true then CL() end
if CMM[17] == true then GT() end
if CMM[18] == true then GT2() end
if CMM[19] == true then ACID() end
if CMM[20] == true then STT() end
if CMM[21] == true then BLS() end
if CMM[22] == true then VTT() end
if CMM[23] == true then BBS() end
if CMM[24] == true then CCS() end
if CMM[25] == true then CRGB() end
if CMM[26] == true then FUNCTIONSRUS() end 
end
end
function RMMGR()
RM = gg.multiChoice({"[1] Слабая Отдача","[2] Нет Отдачи","[НАЗАД]"}, nil, 'Меню Отдачи ИСПОЛЬЗОВАТЬ В ЛОББИ')
if RM == nil then

else
if RM[1] == true then LLR() end
if RM[2] == true then NOR() end
if RM[3] == true then FUNCTIONSRUS() end 
end
end
function MBMMR()
MB = gg.multiChoice({"[1] Магическая Пуля v4","[2] Магическая Пуля v5","[3] Магическая Пуля v6","[НАЗАД]"}, nil, 'Меню Магической Пули ИСПОЛЬЗОВАТЬ В ИГРЕ')
if MB == nil then

else
if MB[1] == true then MB11() end
if MB[2] == true then MB77() end
if MB[3] == true then MB666() end
if MB[4] == true then FUNCTIONSRUS() end 
end
end
function WHMMR()
WHH = gg.multiChoice({"[1] Видеть Противника Сквозь Стены v1","[2] Видеть Противника Сквозь Стены v2","[3] Видеть Противника Сквозь Стены v3","[4] Видеть Предметы Сквозь Стены","[5] Стрелять Сквозь Стены","[НАЗАД]"}, nil, 'Меню Взлома Сквозь Стены ИСПОЛЬЗОВАТЬ В ИГРЕ')
if WHH == nil then

else
if WHH[1] == true then PLAYER() end
if WHH[2] == true then snappp() end
if WHH[3] == true then PWHV3() end
if WHH[4] == true then ITEM() end
if WHH[5] == true then WALLS() end
if WHH[6] == true then FUNCTIONSRUS() end 
end
end

function LANGRUS()
LG = gg.choice({'[1] ENGLISH','[2] РУССКИЙ','[НАЗАД]'},nil,'Choose your language\nВыбери свой язык')
if LG == 1 then HOME() end
if LG == 2 then RUS() end
if LG == 3 then RUS() end
end
function RUS()
RU = gg.choice({'[BYPASS]','[ФУНКЦИИ]','[ЯЗЫК]','[ИЗМЕНЕНИЯ]','[ВЫХОД]'}, nil,' ▰ ▱ ARA HACK ▰ ▱ \n      PUBG: 0.7.0  ▎SCRIPT v 3.3\n            MADE BY 𒈞PLAYDF25\n                          https://t.me/ARA_HACK')
if RU == 1 then BYPASS() end
if RU == 2 then FUNCTIONSRUS() end
if RU == 3 then LANGRUS() end
if RU == 4 then NEWS() end
if RU == 5 then EXIT() end
end

function NEWS()
gg.alert("------------ ARA HACK 3.3\nNew: Returned Bypass in menu, WallShot, Auto HeadShot, New Magic Bullet.\n------------ ARA HACK 3.2\nNew: Redesigned Interface, Bypass, Magic Bullet, Colors, Antenna Always v2, Equipment Antenna, No Grass/Houses, Lift Sit Down Aim, Lift Sit, Multi Jump.")
end

function ACID()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("256;8200;16;15", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(180)
gg.editAll("6", gg.TYPE_DWORD)
gg.toast('Body Acid has been active')
gg.clearResults()
end

function BYPASS()
  gg.searchNumber("1.2F;1.8F:9::1", gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1.1F;1.4F:3::1", gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1.1D;1.4D:2::10", gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
  gg.clearResults()
  gg.searchNumber("5001;1.1;1F::10", gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.searchNumber("1.2F;1.8F:9::1", gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1.1F;1.4F:3::1", gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1.1D;1.4D:2::10", gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
  gg.clearResults(850)
end

function MB77()
  gg.clearResults()
  gg.searchNumber("1,104,805,888D;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(250)
  gg.editAll("75", gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.searchNumber("15;28;16;26;8;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(56)
  gg.editAll("60", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Magic Bullet v5")
end

function GT2()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("538968080D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("538968080", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("-999", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Body Gradient v2 has been active")
end

function GT()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("1,669,433,347", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1000)
gg.editAll("99999999", gg.TYPE_DWORD)
gg.clearResults()
gg.toast('Body Gradient v1 has been active')
end

function CRGB()
gg.clearResults()
gg.setRanges (gg.REGION_BAD) gg.searchNumber('8200;1,080,035,591::512', 4, false, 536870912, 0, -1)
gg.searchNumber('8200', 4, false, 536870912, 0, -1)
gg.getResults(10)
gg.editAll('2073252416', 4)
gg.toast('Body Crystal RGB has been active')
gg.clearResults()
end

function MULTJUMP()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults() 
gg.searchNumber("-0.70710676908;0.70710670948;64;128D;1D::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("3", gg.TYPE_DWORD)
gg.clearResults()
  gg.toast("Multi Jump has been active")
end

function CL()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("589826", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(180)
gg.editAll("999999", gg.TYPE_DWORD)
gg.toast("Body Crystal has been active")
gg.clearResults()
end

function EIA()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("7.1689529418945", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(3)
  gg.editAll("999999999", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("3.4779739379883;2.8345839977264;3.1967880725861;3.8841888904572;3.1528658866882::208", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("3.4779739379883", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1)
  gg.editAll("003,005,0", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("7.4993133544922", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("7.4993133544922", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1)
  gg.editAll("999", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("0.73620933294296", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(3)
  gg.editAll("999999999", gg.TYPE_FLOAT)
  gg.toast("Equipment Items Antenna has been active")
end

function NOHOUS()
  gg.clearResults()
  gg.setRanges(gg.REGION_C_BSS)
  gg.searchNumber("2048D;1F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("0.07", gg.TYPE_FLOAT)
  gg.toast("No Grass/Houses has been active")
end

function EMLD()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("8200;16", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("14", gg.TYPE_DWORD)
gg.clearResults()
gg.toast('Body Emerald has been active')
end

function CCS()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.clearResults()
gg.searchNumber("100F;1F;1,008,981,770D:99", gg.TYPE_FLOAT, false, gg.SING_EQUAL, 0, -1)
gg.searchNumber("100", gg.TYPE_FLOAT, false, gg.SING_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("99999", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
end

function PWHV3()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("5.1097599e21;2.0;1.6623071e-19;3.6734297e-39;1.66433e10::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("200", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-5.5693206e-40;4.814603e21;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_BAD) gg.searchNumber("2.0;-1.0;0.0;1.0;-127.0::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("200", gg.TYPE_FLOAT)
gg.toast("Player Wallhack v3 has been active")
gg.clearResults()
end

function RGB()
gg.clearResults()
gg.setRanges(gg.REGION_BAD) gg.searchNumber("8200;1,080,035,591::512", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("0", gg.TYPE_DWORD)
gg.toast('Body RGB has been active')
end

function REDV3()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("256;8200;16;15", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(180)
gg.editAll("7", gg.TYPE_DWORD)
gg.clearResults()
gg.toast('Body Red v2 has been active')
end

function Z4X()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("60;55;1.9618179e-44 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("20", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Zoom X4 has been active")
end

function Z8X()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("60;55;1.9618179e-44 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("13", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Zoom X8 has been active")
end

function Z15X()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("60;55;1.9618179e-44 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("5", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Zoom X15 has been active")
end

function SDDV2() 
  gg.clearResults() 
  gg.setRanges(gg.REGION_ANONYMOUS)   gg.searchNumber("1,092,081,726;1,003,658,240;923,795,456", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1) 
  gg.searchNumber("1,092,081,726", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1) 
  gg.getResults(100) 
  gg.editAll("1,175,081,726", gg.TYPE_DWORD) 
  gg.clearResults() 
  gg.toast("Old Lift Sit Down Aim has been active")  
end

function LSDA()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("1,092,081,726;1,003,658,240;923,795,456", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1,092,081,726", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("1,136,081,726", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("New Lift Sit Down Aim has been active")
end

function MB666()
gg.clearResults()
  gg.searchNumber("1,104,805,888D;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(250)
  gg.editAll("75", gg.TYPE_FLOAT)
gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.searchNumber("15;28;16;26;8;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(56)
  gg.editAll("111", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Magic Bullet v6 has been active")
end

function REDV2()
gg.clearResults()
  gg.setRanges (gg.REGION_BAD)
  gg.searchNumber('8196;256;8204;256;8200', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber('8200', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll('391', gg.TYPE_DWORD)
  gg.toast('Body Red HDR has been active')
  end

function FLYB()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("40.0F;10.0F;50.0F;40 000.0F::13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(25)
gg.editAll("980",gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('Fly Buggies has been active')  
end

function HJJJ()
  gg.clearResults(850)
  gg.toast("Loading...")
  gg.searchNumber("1;35;443;0.5;55;0.57357645035", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(850)
  print("Replaced: ", gg.editAll("0.5", gg.TYPE_FLOAT))
  gg.clearResults(850)
  gg.toast("High Jump has been active")
end

function LIFTW()
gg.clearResults()
 gg.setRanges(gg.REGION_ANONYMOUS)
 gg.searchNumber("1 152 319 488D;1 036 831 949D;1 148 846 080D;1 118 830 592D;60F;1 112 014 848D::25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
 gg.searchNumber("60", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
 gg.getResults(100)
 gg.editAll("-330", gg.TYPE_FLOAT)
 gg.clearResults()
gg.toast("Lift Sit has been active")
end


function VLLL()
  gg.clearResults()
  gg.searchNumber("0.1;1000;88;60;30", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("30", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("-999", gg.TYPE_FLOAT)
  gg.toast("Visual Lift Lying has been active")
end

function BYPASSX3()
gg.toast('BYPASS X3 is working...')
gg.clearResults()
  gg.searchNumber("4,141D;4.7408155e21;-5.5693206e-40;4.814603e21;3.7615819e-37;2: ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.clearResults()
  gg.toast("BYPASS X3 has been actived")
end

function QWS()
  gg.clearResults()
  gg.searchNumber("0.83333331347;1;0.83333331347::321\000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("0.83333331347", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("0.000001", gg.TYPE_FLOAT)
  gg.toast("Quick Weapon Switch activated!")
end

function XAN()
  gg.setRanges(gg.REGION_BAD)
  gg.clearResults()
  gg.searchNumber("3.4779739379883;2.8345839977264;3.1967880725861;3.8841888904572;3.1528658866882::208", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("3.4779739379883", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("003,005,0", gg.TYPE_DWORD)
  gg.toast("X8 Item Antenna has been active")
  gg.clearResults()
end

function DTW()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.searchNumber("982622900;1956496814;1112014847;1103626239", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1956496814", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("1091567616", gg.TYPE_DWORD)
  gg.toast("Drive Through Wall has been active")
  gg.clearResults()
end

function ANR5()
gg.clearResults() 
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("7.13142681122;0.53447723389;22.6400718689", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("7.13142681122;0.53447723389;22.6400718689", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(3)
  gg.editAll("3000", gg.TYPE_FLOAT)
  gg.clearResults()
gg.toast('Antenna v5 has been active')
end

function ANR6()
gg.clearResults()
gg.searchNumber("7.13142681122;0.53447723389;22.6400718689", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("22.6400718689", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("9621", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.searchNumber("0.53446006775F;-1.68741035461F:501", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("-1.68741035461", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1995)
  gg.editAll("19995", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("18.38612365723F;0.54026412964F:5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("18.38612365723F;0.54026412964F:5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1995)
  gg.editAll("19995", gg.TYPE_FLOAT)
  gg.clearResults()
gg.toast("Antenna Always v1 has been active")
end

function FWW()
gg.clearResults()
gg.searchNumber("0;7.0064923e-45;1;100;1;2,500,000,000.0;0.10000000149;88", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("1.8", gg.TYPE_FLOAT)
gg.toast("Fast Walk has been active")
end

function KP()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("76000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("200000", gg.TYPE_FLOAT)
  gg.toast("Kar98k Powershot has been active")
  gg.clearResults()
end

function KAN()
  gg.clearResults()
  gg.searchNumber("1.4943189620972;-2.3106904029846;-1.5036518573761;0.33800649642944;0.19816112518311::340", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1.4943189620972", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.toast("Kar98k Item Antenna has been active")
  gg.clearResults()
end

function BODYB() 
  gg.clearResults()
  gg.searchNumber('0.05499718338;1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber('1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll('0.05', gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.searchNumber('8E;2.5;6.0255834e-44::150 ', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber('2.5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll('99999', gg.TYPE_FLOAT)
  gg.toast('Black Body v1 has been active')
  gg.clearResults()
end

function WHIT2()
gg.clearResults()
gg.toast('Being processed')
gg.searchNumber('0.05499718338;1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll('777', gg.TYPE_FLOAT)
gg.toast('White Body v2 has been active')
end

function WHIT3()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("0.05499718338;1.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.toast("Body White v3 has been active")
end

function BLACK()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("0.05499718338;1.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("-9999", gg.TYPE_FLOAT)
  gg.toast("Body Black v1 has been active")
end

function MISH()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("1;1;1;0.0001;20;0.0005;0.4::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(500)
  gg.editAll("1.04", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Micro SpeedHack has been active")
end

function SOGT()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("4.8883906e21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("4.8883906e21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("4.8883906e20", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("No Grass/Trees v1 has been active")
end

function VXX()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.clearResults()
  gg.searchNumber("220;178;15 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("220", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("1200", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Extended Review has been active")
end

function LLJ()
  gg.clearResults()
  gg.searchNumber("-980.0F;0.30000001192F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("-980", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("-550", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Long Jump has been active")
end

function MB66()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("88.15017700195;15:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("15", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("2500", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("-88.66608428955;26:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("26", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("2500", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("90.4850692749;27.25;28:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("27.25;28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("2500", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Magic Bullet v2 has been active")
end

function NOGT()
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("2;10000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("0", gg.TYPE_FLOAT, FREEZE_NORMAL)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("4.8883906e21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("4.8883906e21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("4.8883906e20", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("No Grass/Trees v2 has been active")
end

function UAZ()
UA = gg.choice({"—— [GAME] Acceleration UAZ ——","—— [GAME] Underwater UAZ ——","________BACK________"}, nil, 'UAZ Menu')
if UA == 1 then AUA() end
if UA == 2 then UAZW() end
if UA == 3 then HOME() end 
end

function WHCAR()
gg.clearResults()
  Fan_searchNumber("5.8518224e-42;1.1101534e-19;4.7424002e21;7.8472714e-44;2.8137513e-40;8.3236568e-40;4.5918309e-40;2.0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  Fan_searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(2)
  gg.editAll("200", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  Fan_searchNumber("1.2218458e-19;2.7550929e-40;288.00006103516;5.8375725e-29;9.18397e-41;3.75000071526;2.5783892e-43;2.0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  Fan_searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(2)
  gg.editAll("200", gg.TYPE_FLOAT)
 gg.clearResults()
gg.searchNumber("4.814603e21;3.5032462e-44;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.toast("25%")
gg.clearResults()
gg.searchNumber("-5.5693206e-40;4.814603e21;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.toast("50%")
gg.clearResults()
gg.searchNumber("-1.0285578e-38;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.toast("75%")
gg.clearResults()
gg.searchNumber("304.00009155273;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.toast("Player/Trans WallHack has been active")
end

function UAZW()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("150;85;45;-129;-85", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber(45, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("99996", gg.TYPE_FLOAT)
gg.clearResults(1314520)
gg.toast("Underwater UAZ has been active")
end

function BYPASSX1()
gg.toast("BYPASS X1 is working...")
gg.searchNumber('1.2F;1.8F:9::1', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.1F;1.4F:3::1', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.1D;1.4D:2::10', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.searchNumber('5001;1.1;1F::10', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.searchNumber('1.2F;1.8F:9::1', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.1F;1.4F:3::1', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.1D;1.4D:2::10', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults(850)
gg.toast("BYPASS X1 has been actived")
end

function BYPASSX2()
gg.toast("BYPASS X2 is working...")
gg.searchNumber('1.2F;1.8F:9::1', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.1F;1.4F:3::1', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.1D;1.4D:2::10', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.searchNumber('5001;1.1;1F::10', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.searchNumber('1.2F;1.8F:9::1', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.1F;1.4F:3::1', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.1D;1.4D:2::10', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults(850)
gg.searchNumber('1.2F;1.8F:9::1', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.1F;1.4F:3::1', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.1D;1.4D:2::10', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.searchNumber('5001;1.1;1F::10', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.searchNumber('1.2F;1.8F:9::1', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.1F;1.4F:3::1', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.1D;1.4D:2::10', gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults(850)
gg.toast("BYPASS X2 has been actived")
end

function SDD()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("1,092,081,726;1,003,658,240;923,795,456", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1,092,081,726", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("1,155,081,726", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("Lift Sit Down Aim has been active")
end

function CBM()
CM = gg.choice({"—— [GAME] Snow Landscape ——","—— [GAME] Black Landspace ——","—— [GAME] Violet Vegetation ——","—— [GAME] Black Sky ——","—— [LOBBY] Body Blue ——","—— [LOBBY] Body Green","—— [LOBBY] Body Red ——","—— [LOBBY] Body Pixel ——","—— [LOBBY] Body Pink ——","—— [LOBBY] Body Yellow ——","—— [LOBBY] Body White ——","________BACK________"}, nil, 'Color Menu')
if CM == 1 then STT() end
if CM == 2 then BLS() end
if CM == 3 then VTT() end
if CM == 4 then BBS() end
if CM == 5 then CB() end
if CM == 6 then CG() end
if CM == 7 then LRB() end
if CM == 8 then PBB() end
if CM == 9 then BBR() end
if CM == 10 then YEL() end
if CM == 11 then WHIT() end
if CM == 12 then HOME() end 
end

function STT()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("3.75000119209;2;2.00000023842;2.00000047684;2.7506108284;3", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("3", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("417", gg.TYPE_FLOAT)
gg.toast("Snow Landscape has been active")
end

function ANR4()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.clearResults()
  gg.searchNumber("18.38613319397F;0.53447723389F;3.42665576935F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)  gg.searchNumber("18.38613319397;0.53447723389;3.42665576935", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(3)
  gg.editAll("26666", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("7.13142681122;0.53447723389;22.6400718689",gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0,-1)
gg.searchNumber("22.6400718689",gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0,-1)
gg.getResults(10)
gg.editAll("96721",gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.clearResults()
gg.searchNumber("7.13142681122;0.53447723389;22.6400718689",gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0,-1)
gg.searchNumber("22.6400718689",gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0,-1)
gg.getResults(10)
gg.editAll("96721",gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Antenna Run Big has been active")
end

function VTT()
gg.clearResults()
gg.searchNumber("589828", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("-99", gg.TYPE_DWORD)
gg.toast("️Violet Vegetation has been active")
end

function CB()
CB = gg.setRanges(gg.REGION_BAD)
gg.clearResults()
gg.searchNumber('589826', gg.TYPE_DWORD, false, gg.SING_EQUAL, 0, -1)
gg.getResults(20050309)
gg.editAll('666666', gg.TYPE_DWORD)
gg.toast("Body Blue has been active")
end

function CG()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber('32,769;-2,134,900,722',gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('32769', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll('32777', gg.TYPE_DWORD)
gg.toast("Body Green has been active")
end

function BBS()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.clearResults()
gg.searchNumber("100F;1F;1,008,981,770D:99", gg.TYPE_FLOAT, false, gg.SING_EQUAL, 0, -1)
gg.searchNumber("100", gg.TYPE_FLOAT, false, gg.SING_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("-99", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.toast("Black Sky has been active")
end

function BBR()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("32,769;-2,134,900,722", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("32769", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("-666", gg.TYPE_DWORD)
gg.toast("Body Pink has been active")
end

function PBB()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("32,769;-2,134,900,722", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("32769", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("30", gg.TYPE_DWORD)
gg.toast("Body Pixel has been active")
end

function LRB()
gg.clearResults()
gg.setRanges (gg.REGION_BAD)
gg.searchNumber("1.4012985e-45;1.0863213e-19;1.4012985e-44\000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1.4012985e-45", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("1.4012985e-44", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber('32,768;-2,134,900,722',gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('32768', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll('32777', gg.TYPE_DWORD)
gg.toast('Body Red has been active')
end

function YEL()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("8200;16", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("14", gg.TYPE_DWORD)
  gg.clearResults()
gg.toast('Body Yellow has been active')
end

function WHIT()
gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
gg.searchNumber("539,246,596;8200D;2.4903147e21F", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
  gg.editAll("8300", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Body White v1 has been active")
end

function BLS()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("3.75000119209;2;2.00000023842;2.00000047684;2.7506108284;3", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("3", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("888", gg.TYPE_FLOAT)
gg.toast("Black Landspace has been active")
end

function ZM()
FG = gg.choice({"—— [GAME] X2 Zoom ——", "—— [GAME] X4 Zoom ——", "—— [GAME] X8 Zoom ——", "—— [GAME] X15 Zoom ——", "________BACK________"}, nil, 'Zoom Menu')
if FG == 1 then X2() end
if FG == 2 then X4() end
if FG == 3 then X8() end 
if FG == 4 then X15() end
if FG == 5 then HOME() end 
end

function X2()
gg.clearResults()
gg.searchNumber("0.38;1::6", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(200)
gg.editAll("1.75", gg.TYPE_FLOAT)
gg.toast("X2 Zoom has been active")
end

function X4()
gg.clearResults()
gg.searchNumber("0.38;1::6", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(200)
gg.editAll("2", gg.TYPE_FLOAT)
gg.toast("X4 Zoom has been active")
end

function X8()
gg.clearResults()
gg.searchNumber("0.38;1::6", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(200)
gg.editAll("2.5", gg.TYPE_FLOAT)
gg.toast("X8 Zoom has been active")
end

function X15()
gg.clearResults()
gg.searchNumber("0.38;1::6", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(200)
gg.editAll("3.0", gg.TYPE_FLOAT)
gg.toast("X15 Zoom has been active")
end

function ARR()
AR = gg.choice({"—— [GAME] Antenna Run Side ——", "—— [GAME] Antenna Run Up ——", "________BACK________"}, nil, 'Antenna Menu')
if AR == 1 then ANR1() end
if AR == 2 then ANR2() end
if AR == 3 then HOME() end 
end

function ANR1()
gg.searchNumber("18.38613319397F;0.53447723389F;3.42665576935F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("18.38613319397;0.53447723389;3.42665576935", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(3)
gg.editAll("6666", gg.TYPE_FLOAT)
gg.toast("Antenna Run Side v1 has been active")
end

function NOR()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.clearResults()
    gg.searchNumber("1868784978;1850305641;28518", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("1868784978", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("1868756421", gg.TYPE_DWORD)
    gg.clearResults()
    gg.searchNumber("1750294898;1415932769;1819307365", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("1750294898;1415932769;1819307365", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1000)
    gg.editAll("100000", gg.TYPE_DWORD)
    gg.clearResults()
    gg.toast("No Recoil has been active")
end

function ANR3()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("18.38613319397F;0.53447723389F;3.42665576935F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("18.38613319397;0.53447723389;3.42665576935", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(3)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("0.99999988079;0.82059580088;1;0.99999988079", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("999", gg.TYPE_FLOAT)
  gg.toast("Antenna Run Side v2 has been active")
end

function ANR7()
  gg.searchNumber("18.38613319397F;0.53447723389F;3.42665576935F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("18.38613319397;0.53447723389;3.42665576935", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(3)
gg.editAll("6666", gg.TYPE_FLOAT)
  gg.searchNumber("0.53446006775F;-1.68741035461F:501", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("-1.68741035461", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1995)
  gg.editAll("19995", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("18.38612365723F;0.54026412964F:5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("18.38612365723F;0.54026412964F:5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1995)
  gg.editAll("19995", gg.TYPE_FLOAT)
  gg.clearResults()
gg.toast("Antenna Always v2 has been active")
end

function ANR2()
gg.clearResults()
gg.searchNumber("7.13142681122;0.53447723389;22.6400718689", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("22.6400718689", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("9621", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Antenna Run Up has been active")
end

function LLR()
(gg.clearResults)()
  ;
  (gg.setRanges)(gg.REGION_ANONYMOUS)
  ;
  (gg.searchNumber)("1.4012985e-45;1;1;1;1;100000::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  ;
  (gg.searchNumber)("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  ;
  (gg.getResults)(100)
  ;
  (gg.editAll)("0.5", gg.TYPE_FLOAT)
  ;
  (gg.toast)("Less Recoil has been active")
end

function WHM()
WG = gg.choice({"—— [LOBBY] Player WallHack ——", "—— [LOBBY] Player WallHack v2 ——", "—— [LOBBY] Player/Trans WallHack ——", "—— [GAME] Item WallHack ——", "________BACK________"}, nil, 'WallHack Menu')
if WG == 1 then PLAYER() end
if WG == 2 then snappp() end
if WG == 3 then PTT() end
if WG == 4 then ITEM() end 
if WG == 5 then HOME() end 
end

function PLAYER()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("4,141D;4.7408155e21;-5.5693206e-40;4.814603e21;3.7615819e-37;2:", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(4)
gg.editAll("120", gg.TYPE_FLOAT)
gg.toast("30%")
gg.clearResults()
gg.searchNumber("-1.0285578e-38;3.7615819e-37;2;-1;1;-127::300", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(4)
gg.editAll("120", gg.TYPE_FLOAT)
gg.toast("60%")
gg.clearResults()
gg.searchNumber("304.00009155273;3.7615819e-37;2;-1;1;-127::240", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(4)
gg.editAll("120", gg.TYPE_FLOAT)
gg.toast("100%")
gg.toast('Player WallHack v1 has been active')
end

function PTT()
 gg.clearResults()
  Fan_searchNumber("5.8518224e-42;1.1101534e-19;4.7424002e21;7.8472714e-44;2.8137513e-40;8.3236568e-40;4.5918309e-40;2.0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  Fan_searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(2)
  gg.editAll("200", gg.TYPE_FLOAT)
  gg.toast("请稍后.....")
  gg.clearResults()
  gg.setRanges(gg.REGION_BAD)
  Fan_searchNumber("1.2218458e-19;2.7550929e-40;288.00006103516;5.8375725e-29;9.18397e-41;3.75000071526;2.5783892e-43;2.0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  Fan_searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(2)
  gg.editAll("200", gg.TYPE_FLOAT)
  gg.toast("物品透视开启成功")
gg.setRanges(gg.REGION_BAD)
  Fan_searchNumber('304.00009155273;3.7615819e-37;2;-1;1;-127::240',gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  Fan_searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll('110',gg.TYPE_FLOAT)
  gg.toast('载具透视开启成功')
 gg.clearResults()
gg.searchNumber("4.814603e21;3.5032462e-44;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.toast("25%")
gg.clearResults()
gg.searchNumber("-5.5693206e-40;4.814603e21;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.toast("50%")
gg.clearResults()
gg.searchNumber("-1.0285578e-38;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.toast("75%")
gg.clearResults()
gg.searchNumber("304.00009155273;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.toast("透视开启完成即将上色")
gg.clearResults()
gg.setRanges (gg.REGION_BAD)
gg.searchNumber('8196;256;8204;256;8200', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('8200', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll('6', gg.TYPE_DWORD)
gg.toast("Player/Trans WallHack has been active")
end

function snappp()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("4.814603e21;3.5032462e-44;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("-5.5693206e-40;4.814603e21;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("5.1848043e-44;-1.0285578e-38;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("304.00009155273;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.toast("Player WallHack v2 has been active")
end

function UMM()
AI = gg.choice({"—— [LOBBY] Micro AimBot ——", "—— [LOBBY] Medium AimBot ——", "—— [LOBBY] Ultra AimBot ——","________BACK________"}, nil, 'AimBot Menu')
if AI == 1 then MICR() end
if AI == 2 then MED() end 
if AI == 3 then UAI() end
if AI == 4 then HOME() end 
end

function MED()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3.5F;1F;1F;1F;200F;20F:512", gg.TYPE_DWORD, false, gg.SING_EQUAL, 0, -1)
gg.searchNumber("200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(850)
gg.editAll("9999", gg.TYPE_FLOAT)

gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3.5F;1F;1F;1F;9999F;20F:512", gg.TYPE_DWORD, false, gg.SING_EQUAL, 0, -1)
gg.searchNumber("3.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(850)
gg.editAll("-9999", gg.TYPE_FLOAT)
gg.clearResults()

gg.toast("Medium AimBot has been active")
end

function UAI()
  gg.clearResults()
  gg.searchNumber("999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("3.5;1;200;20::999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("3.5;1;200;20", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("-1.0e10", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("3.5;1;200;20::999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("3.5;1;200;20::959", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("-9999999999", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Ultra AimBot has been active")
end

function MICR()
MICR = gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.clearResults()
gg.searchNumber('3.5;1;200;20::250 ', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll('9999999999', gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('Micro AimBot v1 has been active')
end

function ITEM()
gg.clearResults()
gg.setRanges (gg.REGION_BAD)
gg.searchNumber('3.7615819e-37;2;-1;1;-127;0.00999999978::49', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('2', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(850)
print('Replaced: ', gg.editAll('7', gg.TYPE_FLOAT))
gg.clearResults()
gg.toast('Item WallHack has been active')
end

function MB22()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("1F;-8.6457681e12F;15F;28F;16F;26F;8F;18F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("15.0F;28.0F;16.0F;26.0F;8.0F;18.0F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(500)
  gg.editAll("160", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Magic Bullet v2 has been active")
end

function MB33()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("1F;-8.6457681e12F;15F;28F;16F;26F;8F;18F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("15.0F;28.0F;16.0F;26.0F;8.0F;18.0F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(500)
  gg.editAll("150", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Magic Bullet v1 has been active")
end

function MB11()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("90.77570343018F;8.0F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(500)
  gg.editAll("100", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Magic Bullet v4 has been active")
end

function NOO()
NO = gg.choice({"—— [GAME] No Grass ——","—— [SPAWN] No Grass/Trees ——","________BACK________"}, nil, 'No Objects Menu')
if NO == 1 then NYT() end
if NO == 2 then NGTT() end
if NO == 3 then HOME() end 
end

function GGG()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.clearResults()
gg.searchNumber('8.0F;1.20000004768F;0.80000001192F;1.5F;0.80000001192F;1.5F:512', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('8', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll('0', gg.TYPE_FLOAT)
gg.toast('No Grass has been active')
end

function AUA()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('0.647058857', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll('-999', gg.TYPE_FLOAT)
gg.toast('Acceleration UAZ has been active')
end

function FRM()
FR = gg.choice({"—— [GAME] M4 ——", "—— [GAME] SC ——", "—— [GAME] AK ——", "________BACK________"}, nil, 'Firing Rate Menu')
if FR == 1 then M4() end
if FR == 2 then SCAR() end 
if FR == 3 then AK47() end
if FR == 4 then HOME() end 
end

function M4()
 gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("30D;10D;0F~1F;257D;3D::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("0.08600000292", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(50)
  gg.editAll("0.04200000272", gg.TYPE_FLOAT)
  gg.toast("M4 Firing Rate has been active")
end

function AK47()
 gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("30D;10D;0F~1F;257D;3D::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("0.10000000149", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(50)
  gg.editAll("0.001", gg.TYPE_FLOAT)
  gg.toast("AK Firing Rate has been active")
end

function WALLS()
gg.setRanges(gg.REGION_C_BSS)
gg.clearResults()
gg.searchNumber("869,711,765D;2;1::55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("0", gg.TYPE_FLOAT)
gg.toast("WallShot has been active")
gg.clearResults()
end

function AUTOHS()
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("-88.66608428955;26:512", gg.TYPE_FLOAT, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
  gg.searchNumber("26", gg.TYPE_FLOAT, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
  var = gg.getResults(2)
  gg.editAll("460", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("-88.73961639404;28:512", gg.TYPE_FLOAT, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
  gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
  var = gg.getResults(2)
  gg.editAll("560", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Auto HeadShot has been active")
end

function SCAR()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("30D;10D;0F~1F;257D;3D::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("0.09600000083", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(50)
  gg.editAll("0.04800000022", gg.TYPE_FLOAT)
  gg.toast("SC Firing Rate has been active")
end

function TBP()
TP = gg.choice({"—— [GAME] Big Player ——","—— [GAME] Small Player ——","________BACK________"}, nil, 'Player Model Menu')
if TP == 1 then BIG() end
if TP == 2 then SMALL() end
if TP == 3 then HOME() end 
end

function BIG()
gg.clearResults()                                                                                                                                                                                                                                                                                                                                   gg.searchNumber('3.0828566e-44;88;88;1;1;1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)                                                                                                                                                                                                                                                                                                                                gg.searchNumber('1', gg.TYPE_FLOAT, false, gg.SIGN_FLOAL, 0, -1)                                                                                                                                                                                                                                                                                                                          gg.getResults(50)                                                                                                                                                                                                                                                                                                                              gg.editAll('1.27', gg.TYPE_FLOAT)                                                                                                                                                                                                                                                                                                                               gg.toast('Big Player Model has been active')                                                                                                                                                                                                                                                                                                                            end

function SMALL()
gg.clearResults()                                                                                                                                                                                                                                                                                                                                   gg.searchNumber('3.0828566e-44;88;88;1;1;1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)                                                                                                                                                                                                                                                                                                                                gg.searchNumber('1', gg.TYPE_FLOAT, false, gg.SIGN_FLOAL, 0, -1)                                                                                                                                                                                                                                                                                                                          gg.getResults(50)                                                                                                                                                                                                                                                                                                                              gg.editAll('0.6', gg.TYPE_FLOAT)                                                                                                                                                                                                                                                                                                                               gg.toast('Small Player Model has been active')                                                                                                                                                                                                                                                                                                                            end


function EXIT()
os.exit()
end

while(true)
do
  if gg.isVisible(true) then
    HOMEDM=1
    gg.setVisible(false) 
  end 
  if HOMEDM==1 then HOME() end
end                                                                                                                                                                                          
