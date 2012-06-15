#FizzBuzz

Question #2 for the Hacker School Summer 2012 Batch application. FizzBuzz in HTML using only CSS pseudo-classes.

<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<!-- saved from url=(0055)http://dl.dropbox.com/u/4209011/hackerschool-app-2.html -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=US-ASCII">
	
	<title>Hacker School Batch 3 App - Trucy Phan</title>
	<meta name="generator" content="TextMate http://macromates.com/">
	<meta name="author" content="Trucy Phan">
	<!-- Date: 2012-04-23 -->
</head>
<body>
	
<style type="text/css">

div {
	text-align: center;
	padding: 1em;
	border: 1px solid #f1f1f1;
	width: 4em;
	height: 4em;
	float: left;
}
div:nth-child(10n+2) {
	clear: both;
}

div:nth-child(3n+1) {
	background-color: #fffb8c;
}

div:nth-child(5n+1) {
	background-color: #95ceff;
}

div:nth-child(15n+1) {
	background-color: #affdb4;
}

div:nth-child(3n+1)::before {
	content: "Fizz";
}

div:nth-child(5n+1)::before {
	content: "Buzz";
}

div:nth-child(15n+1)::before {
	content: "FizzBuzz";
}

div:nth-child(2)::before {content: "1";}
div:nth-child(3)::before {content: "2";}
div:nth-child(5)::before {content: "4";}
div:nth-child(8)::before {content: "7";}
div:nth-child(9)::before {content: "8";}
div:nth-child(12)::before {content: "11";}
div:nth-child(14)::before {content: "13";}
div:nth-child(15)::before {content: "14";}
div:nth-child(17)::before {content: "16";}
div:nth-child(20)::before {content: "19";}
div:nth-child(18)::before {content: "17";}
div:nth-child(19)::before {content: "18";}
div:nth-child(23)::before {content: "22";}
div:nth-child(24)::before {content: "23";}
div:nth-child(27)::before {content: "26";}
div:nth-child(29)::before {content: "28";}
div:nth-child(30)::before {content: "29";}
div:nth-child(32)::before {content: "31";}
div:nth-child(33)::before {content: "32";}
div:nth-child(35)::before {content: "34";}
div:nth-child(38)::before {content: "37";}
div:nth-child(39)::before {content: "38";}
div:nth-child(42)::before {content: "41";}
div:nth-child(44)::before {content: "43";}
div:nth-child(45)::before {content: "44";}
div:nth-child(47)::before {content: "46";}
div:nth-child(48)::before {content: "47";}
div:nth-child(50)::before {content: "49";}
div:nth-child(53)::before {content: "52";}
div:nth-child(54)::before {content: "53";}
div:nth-child(57)::before {content: "56";}
div:nth-child(59)::before {content: "58";}
div:nth-child(60)::before {content: "59";}
div:nth-child(62)::before {content: "61";}
div:nth-child(63)::before {content: "62";}
div:nth-child(65)::before {content: "64";}
div:nth-child(68)::before {content: "67";}
div:nth-child(69)::before {content: "68";}
div:nth-child(72)::before {content: "71";}
div:nth-child(74)::before {content: "73";}
div:nth-child(75)::before {content: "74";}
div:nth-child(77)::before {content: "76";}
div:nth-child(78)::before {content: "77";}
div:nth-child(80)::before {content: "79";}
div:nth-child(83)::before {content: "82";}
div:nth-child(84)::before {content: "83";}
div:nth-child(87)::before {content: "86";}
div:nth-child(89)::before {content: "88";}
div:nth-child(90)::before {content: "89";}
div:nth-child(92)::before {content: "91";}
div:nth-child(93)::before {content: "92";}
div:nth-child(95)::before {content: "94";}
div:nth-child(98)::before {content: "97";}
div:nth-child(99)::before {content: "98";}

</style>

<div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div><div></div>


</body></html>