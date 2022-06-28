# ioquake3 server with custom maps

Clients need to enable "Allow Downloads" either from the Game options menu or from the console: \cl_allowDownload "1"

### server.cfg

seta sv_allowDownload "1"
seta sv_dlURL "https://github.com/teklynk/q3a/raw/master"

### custom.cfg

// Free for all
seta g_gametype 2             // 0:FFA, 1:Tourney, 2:FFA, 3:TD, 4:CTF
seta timelimit 10                 // Time limit in minutes
seta fraglimit 15                 // Frag limit

// Custom maps
set m1 "map padgarden; set nextmap vstr m2"
set m2 "map padkitchen; set nextmap vstr m3"
set m3 "map padshop; set nextmap vstr m4"
set m4 "map reqkitchen; set nextmap vstr m5"
set m5 "map rdogdm4; set nextmap vstr m6"
set m6 "map padcenter; set nextmap vstr m7"
set m7 "map vinyl; set nextmap vstr m8"
set m8 "map obiwanshouse; set nextmap vstr m9"
set m9 "map reqbath; set nextmap vstr m10"
set m10 "map aepyra; set nextmap vstr m11"
set m11 "map 13tokay; set nextmap vstr m12"
set m12 "map instactf1; set nextmap vstr m13"
set m13 "map ts_mod1; set nextmap vstr m14"
set m14 "map 20kdm2; set nextmap vstr m15"
set m15 "map necro6; set nextmap vstr m16"
set m16 "map lit; set nextmap vstr m17"
set m17 "map uzul3; set nextmap vstr m18"
set m18 "map acid3dm9; set nextmap vstr m19"
set m19 "map kamq3dm2; set nextmap vstr m20"
set m20 "map geit3dm6; set nextmap vstr m21"
set m21 "map cht3; set nextmap vstr m22"
set m22 "map crescent; set nextmap vstr m23"
set m23 "map bubtny4; set nextmap vstr m24"
set m24 "map jof3dm2; set nextmap vstr m25"
set m25 "map geit3dm6; set nextmap vstr m26"
set m26 "map rota3dm2; set nextmap vstr m27"
set m27 "map rota3dm3; set nextmap vstr m1"
vstr m1