

/* =========================================================
   ULTIMATE XI MASTER JAVASCRIPT
   ========================================================= */

/* =========================================================
   PLAYER DATABASE
   ========================================================= */

const PLAYER_DATABASE = [

/* =========================================================
   PRESENT PLAYERS
   ========================================================= */

{
id:"courtois",
name:"Thibaut Courtois",
nation:"Belgium",
position:"GK",
alternative:["GK"],
ovr:106,
type:"PRESENT",
emoji:"🧤",
pace:84,
shooting:60,
passing:72,
dribbling:70,
defending:88,
physical:90,
foot:"Left",
skills:1
},

{
id:"hakimi",
name:"Achraf Hakimi",
nation:"Morocco",
position:"RB",
alternative:["RWB","RM"],
ovr:106,
type:"PRESENT",
emoji:"💨",
pace:96,
shooting:78,
passing:84,
dribbling:88,
defending:82,
physical:85,
foot:"Right",
skills:4
},

{
id:"vandijk",
name:"Virgil van Dijk",
nation:"Netherlands",
position:"CB",
alternative:["CDM"],
ovr:106,
type:"PRESENT",
emoji:"🛡️",
pace:86,
shooting:60,
passing:82,
dribbling:70,
defending:96,
physical:95,
foot:"Right",
skills:2
},

{
id:"gabriel",
name:"Gabriel Magalhães",
nation:"Brazil",
position:"CB",
alternative:["LB"],
ovr:105,
type:"PRESENT",
emoji:"🛡️",
pace:78,
shooting:54,
passing:75,
dribbling:62,
defending:91,
physical:94,
foot:"Left",
skills:2
},

{
id:"theo",
name:"Theo Hernández",
nation:"France",
position:"LB",
alternative:["LWB","LM"],
ovr:106,
type:"PRESENT",
emoji:"🔥",
pace:97,
shooting:76,
passing:82,
dribbling:89,
defending:79,
physical:91,
foot:"Left",
skills:4
},

{
id:"rodri",
name:"Rodri",
nation:"Spain",
position:"CDM",
alternative:["CM","CB"],
ovr:106,
type:"PRESENT",
emoji:"🧠",
pace:78,
shooting:82,
passing:94,
dribbling:87,
defending:93,
physical:91,
foot:"Right",
skills:4
},

{
id:"bellingham",
name:"Jude Bellingham",
nation:"England",
position:"CM",
alternative:["CAM","CDM"],
ovr:106,
type:"PRESENT",
emoji:"💫",
pace:88,
shooting:84,
passing:88,
dribbling:91,
defending:81,
physical:89,
foot:"Right",
skills:4
},

{
id:"debruyne",
name:"Kevin De Bruyne",
nation:"Belgium",
position:"CAM",
alternative:["CM","RW"],
ovr:106,
type:"PRESENT",
emoji:"🎯",
pace:80,
shooting:89,
passing:98,
dribbling:88,
defending:63,
physical:78,
foot:"Right",
skills:4
},

{
id:"messi",
name:"Lionel Messi",
nation:"Argentina",
position:"RW",
alternative:["CAM","CF","ST"],
ovr:107,
type:"PRESENT",
emoji:"⭐",
pace:90,
shooting:96,
passing:97,
dribbling:99,
defending:38,
physical:65,
foot:"Left",
skills:5
},

{
id:"ronaldo",
name:"Cristiano Ronaldo",
nation:"Portugal",
position:"ST",
alternative:["LW","CF"],
ovr:107,
type:"PRESENT",
emoji:"👑",
pace:88,
shooting:98,
passing:83,
dribbling:91,
defending:42,
physical:91,
foot:"Right",
skills:5
},

{
id:"mbappe",
name:"Kylian Mbappé",
nation:"France",
position:"LW",
alternative:["ST","RW"],
ovr:107,
type:"PRESENT",
emoji:"⚡",
pace:99,
shooting:96,
passing:85,
dribbling:97,
defending:39,
physical:88,
foot:"Right",
skills:5
},

{
id:"salah",
name:"Mohamed Salah",
nation:"Egypt",
position:"RW",
alternative:["RM","ST"],
ovr:106,
type:"PRESENT",
emoji:"⚡",
pace:95,
shooting:91,
passing:84,
dribbling:94,
defending:45,
physical:76,
foot:"Left",
skills:4
},

{
id:"modric",
name:"Luka Modrić",
nation:"Croatia",
position:"CM",
alternative:["CAM","CDM"],
ovr:105,
type:"PRESENT",
emoji:"🎩",
pace:75,
shooting:82,
passing:96,
dribbling:93,
defending:61,
physical:67,
foot:"Right",
skills:4
},

{
id:"donnarumma",
name:"Gianluigi Donnarumma",
nation:"Italy",
position:"GK",
alternative:["GK"],
ovr:105,
type:"PRESENT",
emoji:"🧤",
pace:76,
shooting:45,
passing:63,
dribbling:53,
defending:90,
physical:88,
foot:"Right",
skills:1
},

{
id:"trent",
name:"Trent Alexander-Arnold",
nation:"England",
position:"RB",
alternative:["RWB","CM"],
ovr:105,
type:"PRESENT",
emoji:"🎯",
pace:80,
shooting:67,
passing:97,
dribbling:83,
defending:72,
physical:74,
foot:"Right",
skills:4
},

{
id:"dias",
name:"Rúben Dias",
nation:"Portugal",
position:"CB",
alternative:["CDM"],
ovr:105,
type:"PRESENT",
emoji:"🛡️",
pace:70,
shooting:50,
passing:76,
dribbling:60,
defending:94,
physical:91,
foot:"Right",
skills:2
},

{
id:"davies",
name:"Alphonso Davies",
nation:"Canada",
position:"LB",
alternative:["LWB","LM"],
ovr:105,
type:"PRESENT",
emoji:"💨",
pace:99,
shooting:61,
passing:79,
dribbling:87,
defending:77,
physical:85,
foot:"Left",
skills:4
},

{
id:"casemiro",
name:"Casemiro",
nation:"Brazil",
position:"CDM",
alternative:["CB","CM"],
ovr:105,
type:"PRESENT",
emoji:"💪",
pace:68,
shooting:72,
passing:77,
dribbling:67,
defending:94,
physical:93,
foot:"Right",
skills:3
},

/* =========================================================
   ICONS
   ========================================================= */

{
id:"cruyff",
name:"Johan Cruyff",
nation:"Netherlands",
position:"CF",
alternative:["ST","CAM","LW"],
ovr:107,
type:"ICON",
emoji:"👑",
pace:94,
shooting:96,
passing:95,
dribbling:98,
defending:43,
physical:76,
foot:"Right",
skills:5
},

{
id:"r9",
name:"Ronaldo Nazário",
nation:"Brazil",
position:"ST",
alternative:["CF"],
ovr:107,
type:"ICON",
emoji:"⚡",
pace:97,
shooting:99,
passing:82,
dribbling:98,
defending:39,
physical:91,
foot:"Right",
skills:5
},

{
id:"pele",
name:"Pelé",
nation:"Brazil",
position:"ST",
alternative:["CAM","CF"],
ovr:107,
type:"ICON",
emoji:"👑",
pace:95,
shooting:99,
passing:96,
dribbling:98,
defending:44,
physical:84,
foot:"Right",
skills:5
},

{
id:"maradona",
name:"Diego Maradona",
nation:"Argentina",
position:"CAM",
alternative:["CF","ST"],
ovr:107,
type:"ICON",
emoji:"⭐",
pace:92,
shooting:94,
passing:98,
dribbling:99,
defending:36,
physical:74,
foot:"Left",
skills:5
},

{
id:"zidane",
name:"Zinedine Zidane",
nation:"France",
position:"CAM",
alternative:["CM","CF"],
ovr:107,
type:"ICON",
emoji:"🎩",
pace:85,
shooting:92,
passing:98,
dribbling:97,
defending:53,
physical:86,
foot:"Right",
skills:5
},

{
id:"ronaldinho",
name:"Ronaldinho",
nation:"Brazil",
position:"LW",
alternative:["CAM","RW"],
ovr:106,
type:"ICON",
emoji:"😁",
pace:93,
shooting:92,
passing:95,
dribbling:99,
defending:38,
physical:82,
foot:"Right",
skills:5
},

{
id:"henry",
name:"Thierry Henry",
nation:"France",
position:"ST",
alternative:["LW","CF"],
ovr:107,
type:"ICON",
emoji:"🔥",
pace:97,
shooting:98,
passing:88,
dribbling:96,
defending:37,
physical:88,
foot:"Right",
skills:5
},

{
id:"eusebio",
name:"Eusébio",
nation:"Portugal",
position:"ST",
alternative:["CF","LW"],
ovr:107,
type:"ICON",
emoji:"🦅",
pace:96,
shooting:99,
passing:84,
dribbling:97,
defending:34,
physical:88,
foot:"Right",
skills:5
},

{
id:"maldini",
name:"Paolo Maldini",
nation:"Italy",
position:"CB",
alternative:["LB"],
ovr:106,
type:"ICON",
emoji:"🛡️",
pace:89,
shooting:54,
passing:84,
dribbling:73,
defending:99,
physical:91,
foot:"Left",
skills:2
},

{
id:"robertocarlos",
name:"Roberto Carlos",
nation:"Brazil",
position:"LB",
alternative:["LWB"],
ovr:106,
type:"ICON",
emoji:"💥",
pace:96,
shooting:91,
passing:88,
dribbling:90,
defending:86,
physical:88,
foot:"Left",
skills:4
},

{
id:"cafu",
name:"Cafu",
nation:"Brazil",
position:"RB",
alternative:["RWB"],
ovr:106,
type:"ICON",
emoji:"💨",
pace:94,
shooting:70,
passing:88,
dribbling:91,
defending:89,
physical:91,
foot:"Right",
skills:4
},

{
id:"xavi",
name:"Xavi",
nation:"Spain",
position:"CM",
alternative:["CDM","CAM"],
ovr:106,
type:"ICON",
emoji:"🎯",
pace:75,
shooting:74,
passing:99,
dribbling:94,
defending:61,
physical:66,
foot:"Right",
skills:4
},

{
id:"iniesta",
name:"Andrés Iniesta",
nation:"Spain",
position:"CM",
alternative:["CAM","LW"],
ovr:106,
type:"ICON",
emoji:"✨",
pace:82,
shooting:78,
passing:98,
dribbling:99,
defending:42,
physical:65,
foot:"Right",
skills:5
},

{
id:"yashin",
name:"Lev Yashin",
nation:"Russia",
position:"GK",
alternative:["GK"],
ovr:106,
type:"ICON",
emoji:"🧤",
pace:72,
shooting:40,
passing:70,
dribbling:50,
defending:99,
physical:94,
foot:"Right",
skills:1
},

{
id:"beckenbauer",
name:"Franz Beckenbauer",
nation:"Germany",
position:"CB",
alternative:["CDM","CM"],
ovr:106,
type:"ICON",
emoji:"🛡️",
pace:86,
shooting:68,
passing:94,
dribbling:81,
defending:97,
physical:87,
foot:"Right",
skills:3
},

{
id:"baresi",
name:"Franco Baresi",
nation:"Italy",
position:"CB",
alternative:["CDM"],
ovr:106,
type:"ICON",
emoji:"🛡️",
pace:83,
shooting:45,
passing:91,
dribbling:68,
defending:99,
physical:88,
foot:"Right",
skills:2
},

{
id:"nesta",
name:"Alessandro Nesta",
nation:"Italy",
position:"CB",
alternative:["RB"],
ovr:106,
type:"ICON",
emoji:"🛡️",
pace:82,
shooting:43,
passing:87,
dribbling:67,
defending:99,
physical:89,
foot:"Right",
skills:2
},

{
id:"carlosalberto",
name:"Carlos Alberto",
nation:"Brazil",
position:"RB",
alternative:["RWB"],
ovr:106,
type:"ICON",
emoji:"💨",
pace:93,
shooting:75,
passing:88,
dribbling:90,
defending:91,
physical:90,
foot:"Right",
skills:4
},

{
id:"matthaus",
name:"Lothar Matthäus",
nation:"Germany",
position:"CM",
alternative:["CDM","CAM"],
ovr:106,
type:"ICON",
emoji:"💪",
pace:92,
shooting:89,
passing:92,
dribbling:88,
defending:86,
physical:93,
foot:"Right",
skills:4
},

{
id:"figo",
name:"Luís Figo",
nation:"Portugal",
position:"RW",
alternative:["RM","CAM"],
ovr:106,
type:"ICON",
emoji:"✨",
pace:90,
shooting:86,
passing:94,
dribbling:97,
defending:35,
physical:78,
foot:"Right",
skills:5
},

{
id:"kaka",
name:"Kaká",
nation:"Brazil",
position:"CAM",
alternative:["CM","CF"],
ovr:106,
type:"ICON",
emoji:"⚡",
pace:94,
shooting:93,
passing:91,
dribbling:95,
defending:35,
physical:84,
foot:"Right",
skills:4
},

{
id:"rivaldo",
name:"Rivaldo",
nation:"Brazil",
position:"CAM",
alternative:["LW","ST"],
ovr:106,
type:"ICON",
emoji:"🎯",
pace:89,
shooting:95,
passing:91,
dribbling:95,
defending:32,
physical:82,
foot:"Left",
skills:5
},

{
id:"romario",
name:"Romário",
nation:"Brazil",
position:"ST",
alternative:["CF"],
ovr:106,
type:"ICON",
emoji:"⚡",
pace:94,
shooting:98,
passing:78,
dribbling:97,
defending:25,
physical:76,
foot:"Right",
skills:5
},

{
id:"best",
name:"George Best",
nation:"Northern Ireland",
position:"RW",
alternative:["LW","CAM"],
ovr:106,
type:"ICON",
emoji:"⭐",
pace:95,
shooting:91,
passing:89,
dribbling:99,
defending:32,
physical:76,
foot:"Right",
skills:5
},

{
id:"charlton",
name:"Bobby Charlton",
nation:"England",
position:"CAM",
alternative:["CM","ST"],
ovr:106,
type:"ICON",
emoji:"🎯",
pace:88,
shooting:96,
passing:93,
dribbling:88,
defending:41,
physical:82,
foot:"Right",
skills:4
},

{
id:"dalglish",
name:"Kenny Dalglish",
nation:"Scotland",
position:"ST",
alternative:["CF","CAM"],
ovr:106,
type:"ICON",
emoji:"👑",
pace:90,
shooting:95,
passing:91,
dribbling:94,
defending:35,
physical:78,
foot:"Right",
skills:5
},

{
id:"vanbasten",
name:"Marco van Basten",
nation:"Netherlands",
position:"ST",
alternative:["CF"],
ovr:106,
type:"ICON",
emoji:"🔥",
pace:89,
shooting:99,
passing:85,
dribbling:92,
defending:28,
physical:87,
foot:"Right",
skills:5
},

{
id:"gullit",
name:"Ruud Gullit",
nation:"Netherlands",
position:"CF",
alternative:["CAM","CM","ST"],
ovr:106,
type:"ICON",
emoji:"💪",
pace:91,
shooting:93,
passing:88,
dribbling:90,
defending:72,
physical:97,
foot:"Right",
skills:5
},

{
id:"vieira",
name:"Patrick Vieira",
nation:"France",
position:"CDM",
alternative:["CM","CB"],
ovr:106,
type:"ICON",
emoji:"💪",
pace:87,
shooting:67,
passing:85,
dribbling:79,
defending:96,
physical:99,
foot:"Right",
skills:3
},

{
id:"makelele",
name:"Claude Makélélé",
nation:"France",
position:"CDM",
alternative:["CM","CB"],
ovr:106,
type:"ICON",
emoji:"🧠",
pace:83,
shooting:42,
passing:81,
dribbling:67,
defending:98,
physical:93,
foot:"Right",
skills:2
},

{
id:"zola",
name:"Gianfranco Zola",
nation:"Italy",
position:"CAM",
alternative:["CF","ST"],
ovr:106,
type:"ICON",
emoji:"✨",
pace:88,
shooting:91,
passing:90,
dribbling:97,
defending:29,
physical:67,
foot:"Right",
skills:5
},

{
id:"delpiero",
name:"Alessandro Del Piero",
nation:"Italy",
position:"ST",
alternative:["CF","CAM","LW"],
ovr:106,
type:"ICON",
emoji:"⭐",
pace:87,
shooting:95,
passing:90,
dribbling:96,
defending:28,
physical:72,
foot:"Right",
skills:5
},

{
id:"totti",
name:"Francesco Totti",
nation:"Italy",
position:"CAM",
alternative:["CF","ST"],
ovr:106,
type:"ICON",
emoji:"🎯",
pace:76,
shooting:95,
passing:97,
dribbling:91,
defending:33,
physical:78,
foot:"Right",
skills:4
},

{
id:"batistuta",
name:"Gabriel Batistuta",
nation:"Argentina",
position:"ST",
alternative:["CF"],
ovr:106,
type:"ICON",
emoji:"💥",
pace:88,
shooting:99,
passing:72,
dribbling:85,
defending:29,
physical:94,
foot:"Right",
skills:4
},

{
id:"crespo",
name:"Hernán Crespo",
nation:"Argentina",
position:"ST",
alternative:["CF"],
ovr:106,
type:"ICON",
emoji:"🔥",
pace:90,
shooting:97,
passing:73,
dribbling:88,
defending:25,
physical:89,
foot:"Right",
skills:4
},

{
id:"zanetti",
name:"Javier Zanetti",
nation:"Argentina",
position:"RB",
alternative:["LB","CM","RWB"],
ovr:106,
type:"ICON",
emoji:"💨",
pace:90,
shooting:61,
passing:89,
dribbling:84,
defending:94,
physical:95,
foot:"Right",
skills:3
},

{
id:"riquelme",
name:"Juan Román Riquelme",
nation:"Argentina",
position:"CAM",
alternative:["CM"],
ovr:106,
type:"ICON",
emoji:"🎩",
pace:68,
shooting:85,
passing:99,
dribbling:94,
defending:29,
physical:67,
foot:"Right",
skills:5
},

{
id:"socrates",
name:"Sócrates",
nation:"Brazil",
position:"CAM",
alternative:["CM","CF"],
ovr:106,
type:"ICON",
emoji:"🎯",
pace:79,
shooting:92,
passing:96,
dribbling:90,
defending:41,
physical:89,
foot:"Right",
skills:4
},

{
id:"jairzinho",
name:"Jairzinho",
nation:"Brazil",
position:"RW",
alternative:["LW","ST"],
ovr:106,
type:"ICON",
emoji:"⚡",
pace:96,
shooting:96,
passing:84,
dribbling:95,
defending:27,
physical:86,
foot:"Right",
skills:5
},

{
id:"garrincha",
name:"Garrincha",
nation:"Brazil",
position:"RW",
alternative:["LW"],
ovr:106,
type:"ICON",
emoji:"✨",
pace:98,
shooting:90,
passing:88,
dribbling:99,
defending:22,
physical:77,
foot:"Right",
skills:5
},

{
id:"didi",
name:"Didi",
nation:"Brazil",
position:"CM",
alternative:["CAM","CDM"],
ovr:106,
type:"ICON",
emoji:"🎯",
pace:80,
shooting:85,
passing:98,
dribbling:93,
defending:44,
physical:76,
foot:"Right",
skills:4
},

/* =========================================================
   HEROES
   ========================================================= */

{
id:"lizarazu",
name:"Bixente Lizarazu",
nation:"France",
position:"LB",
alternative:["LWB"],
ovr:106,
type:"HERO",
emoji:"💨",
pace:91,
shooting:61,
passing:82,
dribbling:84,
defending:90,
physical:85,
foot:"Left",
skills:3
},

{
id:"stam",
name:"Jaap Stam",
nation:"Netherlands",
position:"CB",
alternative:["RB"],
ovr:106,
type:"HERO",
emoji:"🛡️",
pace:86,
shooting:42,
passing:70,
dribbling:51,
defending:97,
physical:99,
foot:"Right",
skills:2
},

{
id:"milito",
name:"Diego Milito",
nation:"Argentina",
position:"ST",
alternative:["CF"],
ovr:106,
type:"HERO",
emoji:"🔥",
pace:84,
shooting:96,
passing:75,
dribbling:87,
defending:24,
physical:88,
foot:"Right",
skills:4
},

{
id:"gomez",
name:"Mario Gómez",
nation:"Germany",
position:"ST",
alternative:["CF"],
ovr:106,
type:"HERO",
emoji:"💥",
pace:83,
shooting:96,
passing:68,
dribbling:79,
defending:21,
physical:94,
foot:"Right",
skills:3
},

{
id:"dinatale",
name:"Antonio Di Natale",
nation:"Italy",
position:"ST",
alternative:["LW","CF"],
ovr:106,
type:"HERO",
emoji:"⚡",
pace:92,
shooting:95,
passing:79,
dribbling:94,
defending:25,
physical:74,
foot:"Right",
skills:5
},

{
id:"marchisio",
name:"Claudio Marchisio",
nation:"Italy",
position:"CM",
alternative:["CDM","CAM"],
ovr:106,
type:"HERO",
emoji:"✨",
pace:83,
shooting:78,
passing:89,
dribbling:86,
defending:77,
physical:82,
foot:"Right",
skills:4
},

{
id:"cahill",
name:"Tim Cahill",
nation:"Australia",
position:"CAM",
alternative:["CM","ST"],
ovr:106,
type:"HERO",
emoji:"💪",
pace:78,
shooting:88,
passing:75,
dribbling:77,
defending:62,
physical:93,
foot:"Right",
skills:3
},

{
id:"okocha",
name:"Jay-Jay Okocha",
nation:"Nigeria",
position:"CAM",
alternative:["RW","LW"],
ovr:106,
type:"HERO",
emoji:"😁",
pace:91,
shooting:84,
passing:92,
dribbling:99,
defending:25,
physical:74,
foot:"Right",
skills:5
},

{
id:"abedi",
name:"Abedi Pelé",
nation:"Ghana",
position:"CAM",
alternative:["LW","RW"],
ovr:106,
type:"HERO",
emoji:"⭐",
pace:91,
shooting:88,
passing:92,
dribbling:96,
defending:27,
physical:75,
foot:"Right",
skills:5
},

{
id:"crouch",
name:"Peter Crouch",
nation:"England",
position:"ST",
alternative:["CF"],
ovr:105,
type:"HERO",
emoji:"💥",
pace:61,
shooting:83,
passing:72,
dribbling:61,
defending:20,
physical:98,
foot:"Right",
skills:3
},

{
id:"keane",
name:"Robbie Keane",
nation:"Ireland",
position:"ST",
alternative:["CF"],
ovr:106,
type:"HERO",
emoji:"🔥",
pace:87,
shooting:92,
passing:77,
dribbling:86,
defending:25,
physical:79,
foot:"Right",
skills:4
},

{
id:"larsson",
name:"Henrik Larsson",
nation:"Sweden",
position:"ST",
alternative:["CF","LW"],
ovr:106,
type:"HERO",
emoji:"🔥",
pace:88,
shooting:97,
passing:76,
dribbling:87,
defending:23,
physical:88,
foot:"Right",
skills:4
},

{
id:"forlan",
name:"Diego Forlán",
nation:"Uruguay",
position:"ST",
alternative:["CF"],
ovr:106,
type:"HERO",
emoji:"💥",
pace:90,
shooting:97,
passing:81,
dribbling:87,
defending:22,
physical:84,
foot:"Right",
skills:4
},

{
id:"cordoba",
name:"Iván Córdoba",
nation:"Colombia",
position:"CB",
alternative:["RB"],
ovr:106,
type:"HERO",
emoji:"🛡️",
pace:95,
shooting:35,
passing:71,
dribbling:57,
defending:95,
physical:91,
foot:"Right",
skills:2
},

{
id:"carvalho",
name:"Ricardo Carvalho",
nation:"Portugal",
position:"CB",
alternative:["CDM"],
ovr:106,
type:"HERO",
emoji:"🛡️",
pace:82,
shooting:40,
passing:78,
dribbling:59,
defending:96,
physical:88,
foot:"Right",
skills:2
},

{
id:"joecole",
name:"Joe Cole",
nation:"England",
position:"CAM",
alternative:["RW","LW"],
ovr:106,
type:"HERO",
emoji:"✨",
pace:88,
shooting:84,
passing:85,
dribbling:94,
defending:26,
physical:71,
foot:"Right",
skills:5
},

{
id:"litmanen",
name:"Jari Litmanen",
nation:"Finland",
position:"CAM",
alternative:["CF","ST"],
ovr:106,
type:"HERO",
emoji:"🎯",
pace:73,
shooting:91,
passing:94,
dribbling:88,
defending:25,
physical:65,
foot:"Right",
skills:4
},

{
id:"mostovoi",
name:"Aleksandr Mostovoi",
nation:"Russia",
position:"CAM",
alternative:["CM","CF"],
ovr:105,
type:"HERO",
emoji:"🎩",
pace:79,
shooting:83,
passing:90,
dribbling:91,
defending:27,
physical:69,
foot:"Right",
skills:4
},

{
id:"nakata",
name:"Hidetoshi Nakata",
nation:"Japan",
position:"CAM",
alternative:["CM","RW"],
ovr:106,
type:"HERO",
emoji:"✨",
pace:82,
shooting:84,
passing:91,
dribbling:87,
defending:40,
physical:77,
foot:"Right",
skills:4
},

{
id:"park",
name:"Park Ji-Sung",
nation:"South Korea",
position:"CM",
alternative:["LM","RM","CAM"],
ovr:106,
type:"HERO",
emoji:"💨",
pace:91,
shooting:69,
passing:82,
dribbling:81,
defending:78,
physical:92,
foot:"Right",
skills:3
},

{
id:"marquez",
name:"Rafael Márquez",
nation:"Mexico",
position:"CB",
alternative:["CDM"],
ovr:106,
type:"HERO",
emoji:"🛡️",
pace:75,
shooting:46,
passing:91,
dribbling:64,
defending:94,
physical:87,
foot:"Right",
skills:2
},

{
id:"campos",
name:"Jorge Campos",
nation:"Mexico",
position:"GK",
alternative:["GK"],
ovr:105,
type:"HERO",
emoji:"🧤",
pace:78,
shooting:42,
passing:66,
dribbling:56,
defending:91,
physical:83,
foot:"Right",
skills:1
},

{
id:"giuly",
name:"Ludovic Giuly",
nation:"France",
position:"RW",
alternative:["RM","ST"],
ovr:106,
type:"HERO",
emoji:"⚡",
pace:93,
shooting:83,
passing:79,
dribbling:92,
defending:29,
physical:70,
foot:"Right",
skills:4
},

{
id:"berbatov",
name:"Dimitar Berbatov",
nation:"Bulgaria",
position:"ST",
alternative:["CF","CAM"],
ovr:106,
type:"HERO",
emoji:"🎯",
pace:74,
shooting:94,
passing:85,
dribbling:91,
defending:22,
physical:79,
foot:"Right",
skills:4
},

{
id:"fowler",
name:"Robbie Fowler",
nation:"England",
position:"ST",
alternative:["CF"],
ovr:106,
type:"HERO",
emoji:"🔥",
pace:81,
shooting:97,
passing:72,
dribbling:85,
defending:20,
physical:78,
foot:"Left",
skills:4
},

{
id:"owen",
name:"Michael Owen",
nation:"England",
position:"ST",
alternative:["CF"],
ovr:106,
type:"HERO",
emoji:"⚡",
pace:97,
shooting:95,
passing:67,
dribbling:91,
defending:18,
physical:72,
foot:"Right",
skills:4
},

{
id:"anelka",
name:"Nicolas Anelka",
nation:"France",
position:"ST",
alternative:["LW","CF"],
ovr:106,
type:"HERO",
emoji:"🔥",
pace:94,
shooting:91,
passing:73,
dribbling:88,
defending:19,
physical:81,
foot:"Right",
skills:4
},

{
id:"gudjohnsen",
name:"Eiður Guðjohnsen",
nation:"Iceland",
position:"ST",
alternative:["CF","CAM"],
ovr:106,
type:"HERO",
emoji:"💥",
pace:78,
shooting:91,
passing:83,
dribbling:84,
defending:22,
physical:83,
foot:"Right",
skills:4
}

];

/* =========================================================
   DEFAULT STARTING XI
   ========================================================= */

const DEFAULT_STARTERS = [

"courtois",
"hakimi",
"vandijk",
"gabriel",
"theo",
"rodri",
"bellingham",
"debruyne",
"messi",
"ronaldo",
"mbappe"

];

/* =========================================================
   DEFAULT RESERVED
   ========================================================= */

const DEFAULT_RESERVED = [

"modric",
"salah",
"trent",
"dias",
"davies",
"casemiro",
"stam"

];

/* =========================================================
   FORMATION POSITIONS
   ========================================================= */

const FORMATIONS = {

"4-3-3":[

[50,91],
[83,75],
[63,76],
[37,76],
[17,75],
[50,62],
[68,51],
[32,51],
[82,31],
[50,20],
[18,31]

],

"4-4-2":[

[50,91],
[83,75],
[63,76],
[37,76],
[17,75],
[82,52],
[62,57],
[38,57],
[18,52],
[60,25],
[40,25]

],

"4-2-3-1":[

[50,91],
[83,75],
[63,76],
[37,76],
[17,75],
[63,62],
[37,62],
[82,42],
[50,38],
[18,42],
[50,21]

],

"3-4-3":[

[50,91],
[68,73],
[50,77],
[32,73],
[86,52],
[62,55],
[38,55],
[14,52],
[80,30],
[50,23],
[20,30]

],

"3-5-2":[

[50,91],
[68,75],
[50,78],
[32,75],
[82,56],
[63,58],
[50,50],
[37,58],
[18,56],
[60,27],
[40,27]

],

"5-3-2":[

[50,91],
[90,73],
[67,76],
[50,79],
[33,76],
[10,73],
[68,51],
[50,54],
[32,51],
[60,27],
[40,27]

]

};

/* =========================================================
   DEFAULT OPPONENT
   ========================================================= */

const DEFAULT_OPPONENTS = [

"donnarumma",
"trent",
"dias",
"stam",
"davies",
"casemiro",
"modric",
"xavi",
"salah",
"r9",
"forlan"

];

/* =========================================================
   GAME STATE
   ========================================================= */

let gameState = {

gems:150000,

drafts:0,

starters:[...DEFAULT_STARTERS],

reserved:[...DEFAULT_RESERVED],

formation:"4-3-3",

captain:"ronaldo",

draftHistory:[],

freePicksUnlocked:false,

freePick1Taken:false,

freePick2Taken:false,

freePickOptions:[]

};

/* =========================================================
   CURRENT PLAYER MODAL
   ========================================================= */

let selectedPlayerId = null;

let selectedStarterIndex = null;

/* =========================================================
   MATCH STATE
   ========================================================= */

let matchMode = "";

let matchDuration = 0;

let matchRemaining = 0;

let matchTimer = null;

let matchUserScore = 0;

let matchAiScore = 0;

let userMatchPlayers = [];

let opponentMatchPlayers = [];

let selectedMatchPlayer = 0;

let ballPosition = {

x:50,

y:50

};

/* =========================================================
   LOCAL STORAGE
   ========================================================= */

function saveGame() {

localStorage.setItem(
"ultimate_xi_state",
JSON.stringify(gameState)
);

}

/* =========================================================
   LOAD GAME
   ========================================================= */

function loadGame() {

const saved =
localStorage.getItem(
"ultimate_xi_state"
);

if(!saved) {

return;

}

try {

const parsed =
JSON.parse(saved);

gameState = {

...gameState,

...parsed

};

} catch(error) {

console.log(
"Could not load saved game."
);

}

}

/* =========================================================
   PLAYER LOOKUP
   ========================================================= */

function getPlayer(id) {

return PLAYER_DATABASE.find(
player => player.id === id
);

}

/* =========================================================
   GET ALL CLUB PLAYERS
   ========================================================= */

function getClubPlayers() {

const ids = [

...gameState.starters,

...gameState.reserved,

...gameState.draftHistory

.map(item => item.id)

];

const unique = [];

ids.forEach(id => {

if(!unique.includes(id)) {

unique.push(id);

}

});

return unique
.map(id => getPlayer(id))
.filter(Boolean);

}

/* =========================================================
   PAGE NAVIGATION
   ========================================================= */

function showPage(pageId) {

document
.querySelectorAll(
".page,.match-page"
)
.forEach(page => {

page.classList.remove(
"active"
);

});

const page =
document.getElementById(
pageId
);

if(page) {

page.classList.add(
"active"
);

}

document
.querySelectorAll(
".navigation button"
)
.forEach(button => {

button.classList.remove(
"active"
);

});

const map = {

home:"navHome",

matchSelect:"navMatch",

squad:"navSquad",

draft:"navDraft",

club:"navClub",

events:"navEvents",

shop:"navShop",

settings:"navSettings"

};

if(map[pageId]) {

const nav =
document.getElementById(
map[pageId]
);

if(nav) {

nav.classList.add(
"active"
);

}

}

if(pageId === "squad") {

renderSquad();

}

if(pageId === "draft") {

renderDraft();

}

if(pageId === "club") {

renderClub();

}

updateAllUI();

}

/* =========================================================
   UPDATE ALL UI
   ========================================================= */

function updateAllUI() {

updateCurrency();

updateHome();

updateSquadOvr();

updateCaptainSelect();

updateClubCounts();

}

/* =========================================================
   UPDATE CURRENCY
   ========================================================= */

function updateCurrency() {

document
.getElementById(
"gemCount"
)
.textContent =
gameState.gems.toLocaleString();

document
.getElementById(
"homeGemCount"
)
.textContent =
gameState.gems.toLocaleString();

}

/* =========================================================
   HOME
   ========================================================= */

function updateHome() {

const ovr =
calculateSquadOvr();

document
.getElementById(
"homeOvr"
)
.textContent =
ovr;

document
.getElementById(
"homeDraftCount"
)
.textContent =
gameState.drafts +
" / 70";

let freeTaken = 0;

if(gameState.freePick1Taken) {

freeTaken++;

}

if(gameState.freePick2Taken) {

freeTaken++;

}

document
.getElementById(
"homeFreePicks"
)
.textContent =
freeTaken +
" / 2";

}

/* =========================================================
   CALCULATE SQUAD OVR
   ========================================================= */

function calculateSquadOvr() {

const players =
gameState.starters
.map(id => getPlayer(id))
.filter(Boolean);

if(!players.length) {

return 0;

}

const total =
players.reduce(
(sum,player) =>
sum + player.ovr,
0
);

return Math.round(
total / players.length
);

}

/* =========================================================
   UPDATE SQUAD OVR
   ========================================================= */

function updateSquadOvr() {

const ovr =
calculateSquadOvr();

document
.getElementById(
"squadOvr"
)
.textContent =
ovr;

document
.getElementById(
"clubOvr"
)
.textContent =
ovr;

}

/* =========================================================
   CAPTAIN SELECT
   ========================================================= */

function updateCaptainSelect() {

const select =
document.getElementById(
"captainSelect"
);

if(!select) {

return;

}

select.innerHTML = "";

gameState.starters.forEach(id => {

const player =
getPlayer(id);

if(!player) {

return;

}

const option =
document.createElement(
"option"
);

option.value =
player.id;

option.textContent =
player.name;

select.appendChild(
option
);

});

if(gameState.starters.includes(
gameState.captain
)) {

select.value =
gameState.captain;

}

}

/* =========================================================
   CHANGE CAPTAIN
   ========================================================= */

function changeCaptain() {

const select =
document.getElementById(
"captainSelect"
);

gameState.captain =
select.value;

saveGame();

renderSquad();

showToast(
getPlayer(
gameState.captain
).name +
" is now captain."
);

}

/* =========================================================
   TEAM SETTINGS
   ========================================================= */

function saveTeamSettings() {

const value =
document.getElementById(
"teamNameInput"
).value;

localStorage.setItem(
"ultimate_xi_team",
value
);

}

/* =========================================================
   CHANGE FORMATION
   ========================================================= */

function changeFormation() {

const select =
document.getElementById(
"formationSelect"
);

gameState.formation =
select.value;

saveGame();

renderSquad();

showToast(
"Formation changed to " +
gameState.formation
);

}

/* =========================================================
   RENDER SQUAD
   ========================================================= */

function renderSquad() {

const select =
document.getElementById(
"formationSelect"
);

if(select) {

select.value =
gameState.formation;

}

renderPitch();

renderReserves();

updateSquadOvr();

updateCaptainSelect();

}

/* =========================================================
   RENDER PITCH
   ========================================================= */

function renderPitch() {

const pitch =
document.getElementById(
"squadPitch"
);

if(!pitch) {

return;

}

pitch
.querySelectorAll(
".squad-player-node"
)
.forEach(node =>
node.remove()
);

const positions =
FORMATIONS[
gameState.formation
] ||
FORMATIONS["4-3-3"];

gameState.starters.forEach(
(id,index) => {

const player =
getPlayer(id);

if(!player) {

return;

}

const position =
positions[index] ||
[50,50];

const node =
document.createElement(
"div"
);

node.className =
"squad-player-node";

node.style.left =
position[0] + "%";

node.style.top =
position[1] + "%";

node.onclick =
() =>
openPlayerDetails(
player.id,
"starter",
index
);

const face =
document.createElement(
"div"
);

face.className =
"node-face";

if(player.id ===
gameState.captain) {

face.classList.add(
"captain"
);

}

face.textContent =
player.emoji;

const label =
document.createElement(
"div"
);

label.className =
"node-label";

label.textContent =
player.name;

const ovr =
document.createElement(
"div"
);

ovr.className =
"node-ovr";

ovr.textContent =
player.ovr;

const pos =
document.createElement(
"div"
);

pos.className =
"node-position";

pos.textContent =
player.position;

node.appendChild(
face
);

node.appendChild(
label
);

node.appendChild(
ovr
);

node.appendChild(
pos
);

pitch.appendChild(
node
);

});

}

/* =========================================================
   RENDER RESERVED
   ========================================================= */

function renderReserves() {

const grid =
document.getElementById(
"reservesGrid"
);

if(!grid) {

return;

}

grid.innerHTML = "";

gameState.reserved.forEach(
(id,index) => {

const player =
getPlayer(id);

if(!player) {

return;

}

const card =
document.createElement(
"div"
);

card.className =
"reserve-slot";

card.onclick =
() =>
openPlayerDetails(
player.id,
"reserved",
index
);

card.innerHTML = `

<div class="reserve-slot-header">

<span>
RESERVED ${index + 1}
</span>

<span class="gold">
${player.ovr}
</span>

</div>

<div class="reserve-slot-player">

<div class="reserve-slot-face">
${player.emoji}
</div>

<div>

<div class="reserve-slot-name">
${player.name}
</div>

<div class="reserve-slot-meta">
${player.position}
•
${player.nation}
</div>

</div>

</div>

`;

grid.appendChild(card);

});

}

/* =========================================================
   PLAYER CARD HTML
   ========================================================= */

function playerCardHTML(
player,
clickAction=""
) {

const typeClass =
player.type === "ICON"
? "icon"
: player.type === "HERO"
? "hero"
: "present";

return `

<div
class="player-card ${typeClass}"
onclick="${clickAction}">

<div class="card-shine"></div>

<div class="card-ovr">
${player.ovr}
</div>

<div class="card-position">
${player.position}
</div>

<div class="card-type">
${player.type}
</div>

<div class="card-face">
${player.emoji}
</div>

<div class="card-name">
${player.name}
</div>

<div class="card-nation">
${player.nation}
</div>

<div class="card-rating-line">
<span>
⚡ ${player.pace}
</span>

<span>
🎯 ${player.shooting}
</span>

<span>
🧠 ${player.passing}
</span>

</div>

</div>

`;

}

/* =========================================================
   OPEN PLAYER DETAILS
   ========================================================= */

function openPlayerDetails(
playerId,
source="club",
starterIndex=null
) {

const player =
getPlayer(playerId);

if(!player) {

return;

}

selectedPlayerId =
playerId;

selectedStarterIndex =
starterIndex;

const modal =
document.getElementById(
"playerModal"
);

const content =
document.getElementById(
"playerModalContent"
);

const isStarter =
source === "starter";

content.innerHTML = `

<div class="player-detail-layout">

<div class="player-detail-card">

${playerCardHTML(
player,
""
)}

</div>

<div class="player-detail-info">

<div class="detail-top">

<div>

<div class="detail-name">
${player.name}
</div>

<div class="detail-meta">
${player.nation}
•
${player.position}
•
${player.type}
</div>

</div>

<div class="detail-ovr">
${player.ovr}
</div>

</div>

<div class="stat-grid">

<div class="stat-box">

<div class="stat-name">
Pace
</div>

<div class="stat-number">
${player.pace}
</div>

</div>

<div class="stat-box">

<div class="stat-name">
Shooting
</div>

<div class="stat-number">
${player.shooting}
</div>

</div>

<div class="stat-box">

<div class="stat-name">
Passing
</div>

<div class="stat-number">
${player.passing}
</div>

</div>

<div class="stat-box">

<div class="stat-name">
Dribbling
</div>

<div class="stat-number">
${player.dribbling}
</div>

</div>

<div class="stat-box">

<div class="stat-name">
Defending
</div>

<div class="stat-number">
${player.defending}
</div>

</div>

<div class="stat-box">

<div class="stat-name">
Physical
</div>

<div class="stat-number">
${player.physical}
</div>

</div>

</div>

<div class="detail-list">

<div class="detail-item">

<span>
Preferred Foot
</span>

<b>
${player.foot}
</b>

</div>

<div class="detail-item">

<span>
Skill Moves
</span>

<b>
${player.skills} ★
</b>

</div>

<div class="detail-item">

<span>
Primary Position
</span>

<b>
${player.position}
</b>

</div>

<div class="detail-item">

<span>
Card Type
</span>

<b>
${player.type}
</b>

</div>

</div>

<div class="alt-position-box">

<div class="alt-title">
ALTERNATIVE POSITIONS
</div>

<div class="position-pills">

${player.alternative
.map(
position =>
`<div class="position-pill">
${position}
</div>`
)
.join("")}

</div>

</div>

<div class="modal-actions">

${
isStarter
?
`
<button
class="replace-button"
onclick="openReplaceForStarter()">
REPLACE PLAYER
</button>
`
:
""
}

<button
class="secondary-button"
onclick="closePlayerModal()">
CLOSE
</button>

</div>

</div>

</div>

`;

modal.classList.add(
"open"
);

}

/* =========================================================
   CLOSE PLAYER MODAL
   ========================================================= */

function closePlayerModal() {

document
.getElementById(
"playerModal"
)
.classList.remove(
"open"
);

}

/* =========================================================
   OPEN REPLACE
   ========================================================= */

function openReplaceForStarter() {

if(
selectedStarterIndex === null
) {

return;

}

const starter =
getPlayer(
gameState.starters[
selectedStarterIndex
]
);

if(!starter) {

return;

}

closePlayerModal();

openReplacementList(
starter,
selectedStarterIndex
);

}

/* =========================================================
   OPEN REPLACEMENT LIST
   ========================================================= */

function openReplacementList(
starter,
starterIndex
) {

const overlay =
document.getElementById(
"replaceOverlay"
);

const grid =
document.getElementById(
"eligibleGrid"
);

const heading =
document.getElementById(
"replaceSubheading"
);

heading.innerHTML = `

Replacing:

<b class="gold">
${starter.name}
</b>

•
Position:

<b>
${starter.position}
</b>

<br>

<span>
Only reserved players who can play
${starter.position} are shown.
</span>

`;

grid.innerHTML = "";

const eligible =
gameState.reserved
.map(id => getPlayer(id))
.filter(Boolean)
.filter(player =>
canPlayPosition(
player,
starter.position
)
);

if(!eligible.length) {

grid.innerHTML = `

<div
style="
grid-column:1/-1;
text-align:center;
padding:40px;
color:#8c99af;
">

No reserved player can play
${starter.position}.

</div>

`;

} else {

eligible.forEach(
player => {

const card =
document.createElement(
"div"
);

card.className =
"reserve-card";

card.onclick = () =>
performReplacement(
starterIndex,
player.id
);

card.innerHTML = `

<div class="reserve-card-top">

<span>
${player.position}
</span>

<span class="gold">
${player.ovr}
</span>

</div>

<div class="reserve-card-face">
${player.emoji}
</div>

<div class="reserve-card-name">
${player.name}
</div>

<div class="reserve-card-meta">
${player.nation}
</div>

<div
class="reserve-card-meta"
style="
color:#f2cc62;
margin-top:7px;
">

Can play:
${[
player.position,
...player.alternative
].join(" • ")}

</div>

<div class="reserve-card-stats">

<div class="reserve-mini-stat">
PAC<br>
<b>${player.pace}</b>
</div>

<div class="reserve-mini-stat">
SHO<br>
<b>${player.shooting}</b>
</div>

<div class="reserve-mini-stat">
DEF<br>
<b>${player.defending}</b>
</div>

</div>

`;

grid.appendChild(
card
);

});

}

overlay.classList.add(
"open"
);

}

/* =========================================================
   POSITION COMPATIBILITY
   ========================================================= */

function canPlayPosition(
player,
position
) {

if(player.position === position) {

return true;

}

if(
player.alternative
.includes(position)
) {

return true;

}

return false;

}

/* =========================================================
   PERFORM REPLACEMENT
   ========================================================= */

function performReplacement(
starterIndex,
reservedPlayerId
) {

const oldStarterId =
gameState.starters[
starterIndex
];

const oldStarter =
getPlayer(
oldStarterId
);

const newPlayer =
getPlayer(
reservedPlayerId
);

if(!oldStarter ||
!newPlayer) {

return;

}

if(
!canPlayPosition(
newPlayer,
oldStarter.position
)
) {

showToast(
"That player cannot play this position."
);

return;

}

/* remove new player from reserved */

gameState.reserved =
gameState.reserved.filter(
id =>
id !== reservedPlayerId
);

/* put old starter into reserved */

gameState.reserved.push(
oldStarterId
);

/* replace starter */

gameState.starters[
starterIndex
] =
reservedPlayerId;

/* captain handling */

if(
gameState.captain === oldStarterId
) {

gameState.captain =
reservedPlayerId;

}

/* save */

saveGame();

/* close */

closeReplaceModal();

/* render */

renderSquad();

renderClub();

updateAllUI();

showToast(
newPlayer.name +
" replaced " +
oldStarter.name
);

}

/* =========================================================
   CLOSE REPLACE MODAL
   ========================================================= */

function closeReplaceModal() {

document
.getElementById(
"replaceOverlay"
)
.classList.remove(
"open"
);

}

/* =========================================================
   FREE PLAYER ADDITION
   ========================================================= */

function addPlayerToClub(
playerId
) {

if(
gameState.starters.includes(
playerId
)
) {

return;

}

if(
gameState.reserved.includes(
playerId
)
) {

return;

}

gameState.reserved.push(
playerId
);

saveGame();

renderReserves();

updateClubCounts();

}

/* =========================================================
   DRAFT ELIGIBLE POOL
   ========================================================= */

function getDraftPool() {

return PLAYER_DATABASE.filter(
player =>
player.ovr >= 105 &&
player.ovr <= 107
);

}

/* =========================================================
   RANDOM DRAFT PLAYER
   ========================================================= */

function getRandomDraftPlayer() {

const pool =
getDraftPool();

return pool[
Math.floor(
Math.random() *
pool.length
)
];

}

/* =========================================================
   OPEN DRAFT
   ========================================================= */

let draftBusy = false;

let currentDraftPlayer = null;

let currentDraftStage = "";

function openDraft() {

if(draftBusy) {

return;

}

if(
gameState.drafts >= 70
) {

if(
!gameState.freePicksUnlocked
) {

gameState.freePicksUnlocked =
true;

saveGame();

}

renderDraft();

showToast(
"70 drafts complete! Free picks unlocked."
);

return;

}

if(
gameState.gems < 2000
) {

showToast(
"Not enough Gems. You need 2,000 Gems."
);

return;

}

gameState.gems -= 2000;

gameState.drafts++;

currentDraftPlayer =
getRandomDraftPlayer();

saveGame();

updateAllUI();

draftBusy = true;

runDraftOpening();

}

/* =========================================================
   DRAFT OPENING
   ========================================================= */

function runDraftOpening() {

const content =
document.getElementById(
"draftContent"
);

content.innerHTML = `

<div
class="draft-pack pack-opening">

<div class="draft-pack-title">
ULTIMATE XI
</div>

<div class="draft-ball">
⚽
</div>

<div class="draft-pack-sub">
OPENING...
</div>

</div>

`;

setTimeout(
() => {

flashDraft();

revealDraftStage(
"NATION",
currentDraftPlayer.nation
);

},
1200
);

}

/* =========================================================
   FLASH
   ========================================================= */

function flashDraft() {

const flash =
document.getElementById(
"draftFlash"
);

flash.classList.remove(
"active"
);

void flash.offsetWidth;

flash.classList.add(
"active"
);

}

/* =========================================================
   REVEAL DRAFT STAGE
   ========================================================= */

function revealDraftStage(
stage,
value
) {

currentDraftStage =
stage;

draftBusy = false;

const content =
document.getElementById(
"draftContent"
);

content.innerHTML = `

<div class="reveal-label">
${stage}
</div>

<div
class="reveal-value reveal-animation">
${value}
</div>

<div class="reveal-subtitle">
The reveal continues...
</div>

<button
class="big-button reveal-button"
onclick="continueDraftReveal()">

CONTINUE

</button>

`;

}

/* =========================================================
   CONTINUE DRAFT REVEAL
   ========================================================= */

function continueDraftReveal() {

if(draftBusy) {

return;

}

draftBusy = true;

if(
currentDraftStage ===
"NATION"
) {

setTimeout(
() => {

revealDraftStage(
"POSITION",
currentDraftPlayer.position
);

},
350
);

return;

}

if(
currentDraftStage ===
"POSITION"
) {

setTimeout(
() => {

revealDraftStage(
"CARD TYPE",
currentDraftPlayer.type
);

},
350
);

return;

}

if(
currentDraftStage ===
"CARD TYPE"
) {

setTimeout(
() => {

revealDraftStage(
"OVR",
currentDraftPlayer.ovr
);

},
350
);

return;

}

if(
currentDraftStage ===
"OVR"
) {

setTimeout(
() => {

showFinalDraftCard();

},
400
);

return;

}

}

/* =========================================================
   FINAL DRAFT CARD
   ========================================================= */

function showFinalDraftCard() {

flashDraft();

draftBusy = false;

const content =
document.getElementById(
"draftContent"
);

content.innerHTML = `

<div class="reveal-label">
PLAYER REVEALED
</div>

<div
style="
animation:revealPop .8s
cubic-bezier(.17,.89,.32,1.3);
">

${playerCardHTML(
currentDraftPlayer,
""
)}

</div>

<div
style="
margin-top:16px;
color:#a6b3c9;
">

${currentDraftPlayer.nation}
•
${currentDraftPlayer.position}
•
${currentDraftPlayer.type}

</div>

<button
class="big-button reveal-button"
onclick="finishDraft()">

ADD TO CLUB

</button>

`;

}

/* =========================================================
   FINISH DRAFT
   ========================================================= */

function finishDraft() {

if(!currentDraftPlayer) {

return;

}

gameState.draftHistory.unshift(
{
id:currentDraftPlayer.id,
time:Date.now()
}
);

/* keep history manageable */

if(
gameState.draftHistory.length > 100
) {

gameState.draftHistory =
gameState.draftHistory.slice(
0,
100
);

}

/* add to reserved */

if(
!gameState.starters.includes(
currentDraftPlayer.id
) &&
!gameState.reserved.includes(
currentDraftPlayer.id
)
) {

gameState.reserved.push(
currentDraftPlayer.id
);

}

/* unlock after 70 */

if(
gameState.drafts >= 70
) {

gameState.freePicksUnlocked =
true;

}

/* save */

saveGame();

const playerName =
currentDraftPlayer.name;

currentDraftPlayer = null;

draftBusy = false;

renderDraft();

renderSquad();

renderClub();

updateAllUI();

showToast(
playerName +
" added to your club!"
);

}

/* =========================================================
   RESET DRAFT SCREEN
   ========================================================= */

function resetDraftOpening() {

draftBusy = false;

currentDraftPlayer = null;

const content =
document.getElementById(
"draftContent"
);

content.innerHTML = `

<div class="draft-pack">

<div class="draft-pack-title">
ULTIMATE XI
</div>

<div class="draft-ball">
⚽
</div>

<div class="draft-pack-sub">
PLAYER DRAFT
</div>

</div>

<button
class="big-button reveal-button"
onclick="openDraft()">

OPEN DRAFT
—
💎 2,000

</button>

`;

}

/* =========================================================
   RENDER DRAFT
   ========================================================= */

function renderDraft() {

const count =
document.getElementById(
"draftCount"
);

const bar =
document.getElementById(
"draftProgressBar"
);

if(count) {

count.textContent =
gameState.drafts;

}

if(bar) {

bar.style.width =
Math.min(
100,
gameState.drafts / 70 * 100
) + "%";

}

renderDraftHistory();

renderFreePicks();

}

/* =========================================================
   DRAFT HISTORY
   ========================================================= */

function renderDraftHistory() {

const history =
document.getElementById(
"draftHistory"
);

if(!history) {

return;

}

if(
!gameState.draftHistory.length
) {

history.innerHTML = `

<div class="muted">
No drafted players yet.
</div>

`;

return;

}

history.innerHTML =
gameState.draftHistory
.slice(0,15)
.map(
item => {

const player =
getPlayer(item.id);

if(!player) {

return "";

}

return `

<div
style="
display:flex;
align-items:center;
gap:12px;
padding:11px 0;
border-bottom:1px solid #17243b;
cursor:pointer;
"
onclick="
openPlayerDetails('${player.id}','club')
">

<div
style="
width:42px;
height:42px;
border-radius:50%;
display:flex;
align-items:center;
justify-content:center;
background:#142039;
font-size:23px;
">

${player.emoji}

</div>

<div
style="
flex:1;
">

<b>
${player.name}
</b>

<div
style="
font-size:10px;
color:#8290a8;
margin-top:3px;
">

${player.nation}
•
${player.position}
•
${player.type}

</div>

</div>

<div
class="gold"
style="
font-size:20px;
font-weight:1000;
">

${player.ovr}

</div>

</div>

`;

}
)
.join("");

}

/* =========================================================
   FREE PICKS
   ========================================================= */

function generateFreePickOptions() {

const pool =
PLAYER_DATABASE.filter(
player =>
player.ovr === 106 ||
player.ovr === 107
);

const options = [];

while(
options.length < 2
) {

const player =
pool[
Math.floor(
Math.random() *
pool.length
)
];

if(
!options.find(
p => p.id === player.id
)
) {

options.push(
player
);

}

}

return options;

}

/* =========================================================
   RENDER FREE PICKS
   ========================================================= */

function renderFreePicks() {

const panel =
document.getElementById(
"freePickPanel"
);

const grid =
document.getElementById(
"freePickGrid"
);

if(!panel || !grid) {

return;

}

if(
!gameState.freePicksUnlocked
) {

panel.style.display =
"none";

return;

}

panel.style.display =
"block";

if(
!gameState.freePickOptions.length
) {

gameState.freePickOptions =
generateFreePickOptions();

saveGame();

}

grid.innerHTML = "";

gameState.freePickOptions
.forEach(
(player,index) => {

const taken =
index === 0
?
gameState.freePick1Taken
:
gameState.freePick2Taken;

const wrapper =
document.createElement(
"div"
);

wrapper.innerHTML =
playerCardHTML(
player,
""
);

const card =
wrapper.firstElementChild;

if(!taken) {

card.addEventListener(
"click",
() =>
takeFreePick(
index
)
);

} else {

card.style.opacity =
".45";

}

grid.appendChild(
wrapper
);

});

}

/* =========================================================
   TAKE FREE PICK
   ========================================================= */

function takeFreePick(index) {

if(index === 0 &&
gameState.freePick1Taken) {

return;

}

if(index === 1 &&
gameState.freePick2Taken) {

return;

}

const player =
gameState.freePickOptions[
index
];

if(!player) {

return;

}

if(index === 0) {

gameState.freePick1Taken =
true;

} else {

gameState.freePick2Taken =
true;

}

if(
!gameState.reserved.includes(
player.id
) &&
!gameState.starters.includes(
player.id
)
) {

gameState.reserved.push(
player.id
);

}

gameState.draftHistory.unshift(
{
id:player.id,
time:Date.now(),
free:true
}
);

saveGame();

renderDraft();

renderSquad();

renderClub();

updateAllUI();

showToast(
player.name +
" added from your FREE PICK!"
);

}

/* =========================================================
   CLUB
   ========================================================= */

let currentClubFilter =
"all";

function renderClub() {

const grid =
document.getElementById(
"clubPlayerGrid"
);

if(!grid) {

return;

}

const players =
getClubPlayers();

const filtered =
players.filter(
player => {

if(
currentClubFilter ===
"all"
) {

return true;

}

return player.type.toLowerCase() ===
currentClubFilter;

}
);

grid.innerHTML = "";

filtered.forEach(
player => {

const wrapper =
document.createElement(
"div"
);

wrapper.innerHTML =
playerCardHTML(
player,
""
);

const card =
wrapper.firstElementChild;

card.addEventListener(
"click",
() =>
openPlayerDetails(
player.id,
gameState.starters.includes(
player.id
)
?
"starter"
:
"club"
)
);

grid.appendChild(
wrapper
);

});

}

/* =========================================================
   CLUB TABS
   ========================================================= */

function showClubTab(
filter
) {

currentClubFilter =
filter;

document
.querySelectorAll(
".club-tab"
)
.forEach(
button =>
button.classList.remove(
"active"
)
);

event
.currentTarget
.classList.add(
"active"
);

renderClub();

}

/* =========================================================
   OPEN CLUB
   ========================================================= */

function openClubPlayers() {

showPage("club");

}

/* =========================================================
   CLUB COUNTS
   ========================================================= */

function updateClubCounts() {

const clubCount =
document.getElementById(
"clubPlayerCount"
);

const reserveCount =
document.getElementById(
"clubReserveCount"
);

if(clubCount) {

clubCount.textContent =
getClubPlayers().length;

}

if(reserveCount) {

reserveCount.textContent =
gameState.reserved.length;

}

}

/* =========================================================
   BUY PLAYER
   ========================================================= */

function buyPlayer() {

if(
gameState.gems < 50000
) {

showToast(
"Not enough Gems."
);

return;

}

gameState.gems -= 50000;

const pool =
PLAYER_DATABASE.filter(
player =>
player.ovr >= 105
);

const player =
pool[
Math.floor(
Math.random() *
pool.length
)
];

if(
!gameState.reserved.includes(
player.id
) &&
!gameState.starters.includes(
player.id
)
) {

gameState.reserved.push(
player.id
);

}

saveGame();

updateAllUI();

renderClub();

renderSquad();

showToast(
player.name +
" purchased for 50,000 Gems."
);

}

/* =========================================================
   TOAST
   ========================================================= */

function showToast(
message
) {

const toast =
document.getElementById(
"toast"
);

toast.textContent =
message;

toast.classList.add(
"show"
);

setTimeout(
() => {

toast.classList.remove(
"show"
);

},
2500
);

}

/* =========================================================
   MATCH START
   ========================================================= */

function startMatch(
mode,
duration
) {

matchMode =
mode;

matchDuration =
duration;

matchRemaining =
duration;

matchUserScore = 0;

matchAiScore = 0;

document
.getElementById(
"userScore"
)
.textContent = "0";

document
.getElementById(
"aiScore"
)
.textContent = "0";

document
.getElementById(
"matchMode"
)
.textContent =
mode.toUpperCase();

showPage("match");

createMatchPlayers();

resetMatchBall();

clearInterval(
matchTimer
);

updateMatchClock();

matchTimer =
setInterval(
() => {

matchRemaining--;

updateMatchClock();

if(
matchRemaining <= 0
) {

finishMatch();

}

},
1000
);

document
.getElementById(
"matchMessage"
)
.textContent =
"Move your player toward the ball.";

}

/* =========================================================
   MATCH CLOCK
   ========================================================= */

function updateMatchClock() {

const minutes =
Math.floor(
matchRemaining / 60
);

const seconds =
matchRemaining % 60;

document
.getElementById(
"matchTimer"
)
.textContent =
String(minutes)
.padStart(2,"0") +
":" +
String(seconds)
.padStart(2,"0");

}

/* =========================================================
   CREATE MATCH PLAYERS
   ========================================================= */

function createMatchPlayers() {

const field =
document.getElementById(
"matchField"
);

field
.querySelectorAll(
".match-player"
)
.forEach(
player =>
player.remove()
);

userMatchPlayers = [];

opponentMatchPlayers = [];

const positions =
FORMATIONS[
gameState.formation
];

gameState.starters
.forEach(
(id,index) => {

const player =
getPlayer(id);

if(!player) {

return;

}

const pos =
positions[index];

const node =
document.createElement(
"div"
);

node.className =
"match-player user";

if(index === 0) {

node.classList.add(
"selected"
);

}

node.textContent =
player.emoji;

node.style.left =
pos[0] + "%";

node.style.top =
pos[1] + "%";

field.appendChild(
node
);

userMatchPlayers.push(
{
id:player.id,
x:pos[0],
y:pos[1],
element:node
}
);

});

const opponentPositions = [

[50,8],
[17,25],
[37,22],
[63,22],
[83,25],
[50,36],
[35,48],
[65,48],
[18,66],
[48,73],
[75,66]

];

DEFAULT_OPPONENTS
.forEach(
(id,index) => {

const player =
getPlayer(id);

if(!player) {

return;

}

const pos =
opponentPositions[index];

const node =
document.createElement(
"div"
);

node.className =
"match-player";

node.textContent =
player.emoji;

node.style.left =
pos[0] + "%";

node.style.top =
pos[1] + "%";

field.appendChild(
node
);

opponentMatchPlayers.push(
{
id:player.id,
x:pos[0],
y:pos[1],
element:node
}
);

});

}

/* =========================================================
   RESET BALL
   ========================================================= */

function resetMatchBall() {

ballPosition.x = 50;

ballPosition.y = 50;

updateMatchBall();

}

/* =========================================================
   UPDATE MATCH BALL
   ========================================================= */

function updateMatchBall() {

const ball =
document.getElementById(
"matchBall"
);

ball.style.left =
ballPosition.x + "%";

ball.style.top =
ballPosition.y + "%";

}

/* =========================================================
   MOVE MATCH PLAYER
   ========================================================= */

function moveMatchPlayer(
dx,
dy
) {

if(!userMatchPlayers.length) {

return;

}

const player =
userMatchPlayers[
selectedMatchPlayer
];

player.x =
Math.max(
3,
Math.min(
97,
player.x + dx
)
);

player.y =
Math.max(
3,
Math.min(
97,
player.y + dy
)
);

player.element.style.left =
player.x + "%";

player.element.style.top =
player.y + "%";

}

/* =========================================================
   SELECT NEAREST PLAYER
   ========================================================= */

function selectNearestMatchPlayer() {

if(!userMatchPlayers.length) {

return;

}

let best = 0;

let bestDistance =
Infinity;

userMatchPlayers
.forEach(
(player,index) => {

const distance =
Math.hypot(
player.x -
ballPosition.x,
player.y -
ballPosition.y
);

if(
distance <
bestDistance
) {

bestDistance =
distance;

best = index;

}

}
);

selectedMatchPlayer =
best;

userMatchPlayers
.forEach(
(player,index) => {

player.element
.classList.toggle(
"selected",
index ===
selectedMatchPlayer
);

}
);

}

/* =========================================================
   GESTURE SYSTEM
   ========================================================= */

function setupGesture(
button,
callback
) {

let startX = 0;

let startY = 0;

button.addEventListener(
"pointerdown",
event => {

startX =
event.clientX;

startY =
event.clientY;

button.setPointerCapture(
event.pointerId
);

}
);

button.addEventListener(
"pointerup",
event => {

const dx =
event.clientX -
startX;

const dy =
event.clientY -
startY;

callback(
dx,
dy
);

}
);

}

/* =========================================================
   SHOOT
   ========================================================= */

setupGesture(
document.getElementById(
"shootButton"
),
(dx,dy) => {

if(!userMatchPlayers.length) {

return;

}

const player =
userMatchPlayers[
selectedMatchPlayer
];

const distance =
Math.hypot(
player.x -
ballPosition.x,
player.y -
ballPosition.y
);

if(
distance > 14
) {

document
.getElementById(
"matchMessage"
)
.textContent =
"Get closer to the ball.";

return;

}

let message =
"SHOT!";

if(
dy < -25
) {

message =
"CHIP SHOT!";

}

else if(
dy > 25
) {

message =
"FINESSE SHOT!";

}

else if(
dx > 25
) {

message =
"POWER SHOT!";

}

else if(
dx < -25
) {

message =
"FAKE SHOT!";

}

const chance =
Math.random();

if(
chance < .68
) {

matchUserScore++;

document
.getElementById(
"userScore"
)
.textContent =
matchUserScore;

document
.getElementById(
"matchMessage"
)
.textContent =
"GOAL! " +
message;

resetMatchBall();

}

else {

document
.getElementById(
"matchMessage"
)
.textContent =
message +
" — SAVED!";

}

}
);

/* =========================================================
   PASS
   ========================================================= */

setupGesture(
document.getElementById(
"passButton"
),
(dx,dy) => {

let message =
"PASS!";

if(
dy < -25
) {

message =
"AIR PASS!";

}

else if(
dy > 25
) {

message =
"BULLET PASS!";

}

document
.getElementById(
"matchMessage"
)
.textContent =
message;

}

/* =========================================================
   THROUGH
   ========================================================= */

setupGesture(
document.getElementById(
"throughButton"
),
(dx,dy) => {

let message =
"THROUGH BALL!";

if(
dy < -25
) {

message =
"AIR THROUGH BALL!";

}

else if(
dy > 25
) {

message =
"BULLET THROUGH BALL!";

}

document
.getElementById(
"matchMessage"
)
.textContent =
message;

}

/* =========================================================
   SPRINT / SKILLS
   ========================================================= */

setupGesture(
document.getElementById(
"sprintButton"
),
(dx,dy) => {

if(
Math.abs(dx) < 20 &&
Math.abs(dy) < 20
) {

moveMatchPlayer(
2.5,
0
);

document
.getElementById(
"matchMessage"
)
.textContent =
"SPRINT!";

return;

}

if(
dy < -25
) {

document
.getElementById(
"matchMessage"
)
.textContent =
"SKILL MOVE 1";

}

else if(
dy > 25
) {

document
.getElementById(
"matchMessage"
)
.textContent =
"SKILL MOVE 2";

}

else if(
dx > 25
) {

document
.getElementById(
"matchMessage"
)
.textContent =
"SKILL MOVE 3";

}

else {

document
.getElementById(
"matchMessage"
)
.textContent =
"SKILL MOVE 4";

}

}
);

/* =========================================================
   JOYSTICK
   ========================================================= */

const joystick =
document.getElementById(
"joystick"
);

const joystickStick =
document.getElementById(
"joystickStick"
);

let joystickActive =
false;

joystick.addEventListener(
"pointerdown",
event => {

joystickActive =
true;

joystick.setPointerCapture(
event.pointerId
);

}
);

joystick.addEventListener(
"pointermove",
event => {

if(!joystickActive) {

return;

}

const rect =
joystick.getBoundingClientRect();

let dx =
event.clientX -
(
rect.left +
rect.width / 2
);

let dy =
event.clientY -
(
rect.top +
rect.height / 2
);

const max =
35;

const distance =
Math.hypot(
dx,
dy
);

if(
distance > max
) {

dx =
dx / distance * max;

dy =
dy / distance * max;

}

joystickStick.style.transform =
"translate(calc(-50% + " +
dx +
"px),calc(-50% + " +
dy +
"px))";

moveMatchPlayer(
dx / max * 1.2,
dy / max * 1.2
);

}
);

function resetJoystick() {

joystickActive =
false;

joystickStick.style.transform =
"translate(-50%,-50%)";

}

joystick.addEventListener(
"pointerup",
resetJoystick
);

joystick.addEventListener(
"pointercancel",
resetJoystick
);

/* =========================================================
   SIMPLE OPPONENT AI
   ========================================================= */

setInterval(
() => {

if(
!matchTimer ||
!opponentMatchPlayers.length
) {

return;

}

opponentMatchPlayers
.forEach(
player => {

const dx =
ballPosition.x -
player.x;

const dy =
ballPosition.y -
player.y;

player.x +=
Math.sign(dx) *
.12;

player.y +=
Math.sign(dy) *
.12;

player.element.style.left =
player.x + "%";

player.element.style.top =
player.y + "%";

}
);

const striker =
opponentMatchPlayers[9];

if(!striker) {

return;

}

const distance =
Math.hypot(
striker.x -
ballPosition.x,
striker.y -
ballPosition.y
);

if(
distance < 7 &&
Math.random() < .018
) {

matchAiScore++;

document
.getElementById(
"aiScore"
)
.textContent =
matchAiScore;

document
.getElementById(
"matchMessage"
)
.textContent =
"Opponent scored!";

resetMatchBall();

}

},
100
);

/* =========================================================
   FINISH MATCH
   ========================================================= */

function finishMatch() {

clearInterval(
matchTimer
);

matchTimer =
null;

let reward = 0;

if(
matchUserScore >
matchAiScore
) {

reward = 100;

}

else if(
matchUserScore ===
matchAiScore
) {

reward = 50;

}

gameState.gems +=
reward;

saveGame();

updateAllUI();

document
.getElementById(
"matchMessage"
)
.textContent =
"FULL TIME — Reward: 💎 " +
reward;

}

/* =========================================================
   END MATCH
   ========================================================= */

function endMatch() {

clearInterval(
matchTimer
);

matchTimer =
null;

showPage(
"matchSelect"
);

}

/* =========================================================
   RESET GAME
   ========================================================= */

function resetGame() {

const answer =
confirm(
"Reset Ultimate XI? Your Gems, drafts and squad changes will be reset."
);

if(!answer) {

return;

}

localStorage.removeItem(
"ultimate_xi_state"
);

localStorage.removeItem(
"ultimate_xi_team"
);

location.reload();

}

/* =========================================================
   INITIALIZATION
   ========================================================= */

loadGame();

/* =========================================================
   TEAM NAME
   ========================================================= */

const savedTeamName =
localStorage.getItem(
"ultimate_xi_team"
);

if(savedTeamName) {

document
.getElementById(
"teamNameInput"
)
.value =
savedTeamName;

}

/* =========================================================
   INITIAL UI
   ========================================================= */

updateAllUI();

renderSquad();

renderDraft();

renderClub();

/* =========================================================
   CLICK OUTSIDE PLAYER MODAL
   ========================================================= */

document
.getElementById(
"playerModal"
)
.addEventListener(
"click",
event => {

if(
event.target.id ===
"playerModal"
) {

closePlayerModal();

}

}
);

/* =========================================================
   CLICK OUTSIDE REPLACE MODAL
   ========================================================= */

document
.getElementById(
"replaceOverlay"
)
.addEventListener(
"click",
event => {

if(
event.target.id ===
"replaceOverlay"
) {

closeReplaceModal();

}

}
);

/* =========================================================
   ESCAPE KEY
   ========================================================= */

document.addEventListener(
"keydown",
event => {

if(
event.key === "Escape"
) {

closePlayerModal();

closeReplaceModal();

}

}
);

/* =========================================================
   AUTO SELECT NEAREST PLAYER
   ========================================================= */

setInterval(
() => {

if(
matchTimer &&
userMatchPlayers.length
) {

selectNearestMatchPlayer();

}

},
1000
);

/* =========================================================
   EXTRA PLAYER UTILITIES
   ========================================================= */

function getPlayerStats(
playerId
) {

const player =
getPlayer(playerId);

if(!player) {

return null;

}

return {

pace:player.pace,

shooting:player.shooting,

passing:player.passing,

dribbling:player.dribbling,

defending:player.defending,

physical:player.physical

};

}

/* =========================================================
   POSITION SEARCH
   ========================================================= */

function getPlayersForPosition(
position
) {

return getClubPlayers()
.filter(
player =>
canPlayPosition(
player,
position
)
);

}

/* =========================================================
   STARTER CHECK
   ========================================================= */

function isStarter(
playerId
) {

return gameState.starters
.includes(
playerId
);

}

/* =========================================================
   RESERVED CHECK
   ========================================================= */

function isReserved(
playerId
) {

return gameState.reserved
.includes(
playerId
);

}

/* =========================================================
   CAPTAIN CHECK
   ========================================================= */

function isCaptain(
playerId
) {

return gameState.captain ===
playerId;

}

/* =========================================================
   SAFE CLUB ADD
   ========================================================= */

function safeAddToReserved(
playerId
) {

if(
isStarter(playerId)
) {

return false;

}

if(
isReserved(playerId)
) {

return false;

}

gameState.reserved.push(
playerId
);

saveGame();

renderSquad();

renderClub();

return true;

}

/* =========================================================
   SAFE REMOVE RESERVED
   ========================================================= */

function removeReserved(
playerId
) {

gameState.reserved =
gameState.reserved.filter(
id =>
id !== playerId
);

saveGame();

renderSquad();

renderClub();

}

/* =========================================================
   SAFE STARTER SWAP
   ========================================================= */

function swapStarterWithReserved(
starterIndex,
reservedId
) {

if(
starterIndex < 0 ||
starterIndex >=
gameState.starters.length
) {

return false;

}

const starterId =
gameState.starters[
starterIndex
];

const starter =
getPlayer(starterId);

const replacement =
getPlayer(reservedId);

if(
!starter ||
!replacement
) {

return false;

}

if(
!canPlayPosition(
replacement,
starter.position
)
) {

return false;

}

const reserveIndex =
gameState.reserved.indexOf(
reservedId
);

if(
reserveIndex === -1
) {

return false;

}

gameState.reserved[
reserveIndex
] =
starterId;

gameState.starters[
starterIndex
] =
reservedId;

if(
gameState.captain ===
starterId
) {

gameState.captain =
reservedId;

}

saveGame();

renderSquad();

renderClub();

updateAllUI();

return true;

}

/* =========================================================
   GET ALTERNATIVE POSITIONS
   ========================================================= */

function getAlternativePositions(
playerId
) {

const player =
getPlayer(playerId);

if(!player) {

return [];

}

return [
...player.alternative
];

}

/* =========================================================
   PLAYER CAN PLAY ANY POSITION
   ========================================================= */

function playerCanPlayAny(
playerId,
positions
) {

const player =
getPlayer(playerId);

if(!player) {

return false;

}

return positions.some(
position =>
canPlayPosition(
player,
position
)
);

}

/* =========================================================
   FIND BEST RESERVED REPLACEMENTS
   ========================================================= */

function getEligibleReservedPlayers(
position
) {

return gameState.reserved
.map(
id => getPlayer(id)
)
.filter(Boolean)
.filter(
player =>
canPlayPosition(
player,
position
)
)
.sort(
(a,b) =>
b.ovr - a.ovr
);

}

/* =========================================================
   FIND BEST CLUB PLAYERS
   ========================================================= */

function getBestPlayersForPosition(
position
) {

return getClubPlayers()
.filter(
player =>
canPlayPosition(
player,
position
)
)
.sort(
(a,b) =>
b.ovr - a.ovr
);

}

/* =========================================================
   PLAYER DETAIL TEXT
   ========================================================= */

function getPlayerSummary(
player
) {

return player.name +
" is a " +
player.ovr +
" OVR " +
player.position +
" from " +
player.nation +
".";

}

/* =========================================================
   DRAFT STATUS
   ========================================================= */

function getDraftStatus() {

return {

paidDrafts:
gameState.drafts,

remaining:
Math.max(
0,
70 - gameState.drafts
),

freeUnlocked:
gameState.freePicksUnlocked,

freePick1Taken:
gameState.freePick1Taken,

freePick2Taken:
gameState.freePick2Taken

};

}

/* =========================================================
   REWARD CALCULATOR
   ========================================================= */

function getMatchReward(
user,
opponent
) {

if(
user > opponent
) {

return 100;

}

if(
user === opponent
) {

return 50;

}

return 0;

}

/* =========================================================
   MODE DURATION
   ========================================================= */

function getModeDuration(
mode
) {

if(
mode ===
"Blitz Attack"
) {

return 80;

}

if(
mode ===
"Pro Match"
) {

return 300;

}

return 80;

}

/* =========================================================
   FORMAT TIME
   ========================================================= */

function formatTime(
seconds
) {

const minutes =
Math.floor(
seconds / 60
);

const secs =
seconds % 60;

return (
String(minutes)
.padStart(2,"0")
+
":"
+
String(secs)
.padStart(2,"0")
);

}

/* =========================================================
   GAME READY
   ========================================================= */

console.log(
"Ultimate XI loaded."
);

console.log(
"Players:",
PLAYER_DATABASE.length
);

console.log(
"Starting XI:",
gameState.starters
);

console.log(
"Reserved:",
gameState.reserved
);

console.log(
"Drafts:",
gameState.drafts
);

