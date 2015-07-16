# jQuery Snippet in /js/hidefieldsScript.js #
```

/*! jQuery script to hide certain form fields */

$(document).ready(function() {

//Hide the field initially
$("#hide1").hide();

//Show the text field only when the third option is chosen - this doesn't
$('#izdrzave').change(function() {
if ($("#izdrzave").val() != "Iz drzave") {
$("#hide1").show();
}
else {
$("#hide1").hide();
}
});

//Hide the field initially
$("#hide2").hide();

//Show the text field only when the third option is chosen - this doesn't
$('#udrzavu').change(function() {
if ($("#udrzavu").val() != "U drzavu") {
$("#hide2").show();
}
else {
$("#hide2").hide();
}
});

//Hide the field initially
$("#hide3").hide();

//Show the text field only when the third option is chosen - this doesn't
$('#udrzavu').change(function() {
if ($("#udrzavu").val() != "U drzavu") {
$("#hide3").show();
}
else {
$("#hide3").hide();
}
});

//Hide the field initially
$("#hide4").hide();

//Show the text field only when the third option is chosen - this doesn't
$('#udrzavu').change(function() {
if ($("#udrzavu").val() != "U drzavu") {
$("#hide4").show();
}
else {
$("#hide4").hide();
}
});

});
```

# CF7 Form Code #
```

<div id="contactForm">

[select izdrzave id:izdrzave class:contactForm "Iz drzave" "Srbija" "Austrija" "Belgija" "Belorusija" "BiH" "Bugarska" "Crna Gora" "Češka Republika" "Čile" "Danska" "Estonija" "Finska" "Francuska" "Grčka" "Holandija" "Hrvatska" "Italija" "Letonija" "Lihtenštajn" "Litvanija" "Luksemburg" "Mađarska" "Makedonija" "Nemačka" "Norveška" "Poljska" "Portugalija" "Rumunija" "Ruska Federacija" "Slovačka" "Slovenija" "Španija" "Švajcarska" "Švedska" "Turska"]</ br>

<div class="hide" id="hide1">
[text izgrada* /50 id:izgrada class:contactForm placeholder "Iz grada"]


Unknown end tag for &lt;/div&gt;

</ br>

[select udrzavu id:udrzavu class:contactForm "U drzavu" "Srbija" "Austrija" "Belgija" "Belorusija" "BiH" "Bugarska" "Crna Gora" "Češka Republika" "Čile" "Danska" "Estonija" "Finska" "Francuska" "Grčka" "Holandija" "Hrvatska" "Italija" "Letonija" "Lihtenštajn" "Litvanija" "Luksemburg" "Mađarska" "Makedonija" "Nemačka" "Norveška" "Poljska" "Portugalija" "Rumunija" "Ruska Federacija" "Slovačka" "Slovenija" "Španija" "Švajcarska" "Švedska" "Turska"]</ br>

<div class="hide" id="hide2">
[text ugrad* id:ugrad class:contactForm placeholder "U grad"]


Unknown end tag for &lt;/div&gt;

</ br>

<div class="hide" id="hide3">
[textarea* predmet x3 placeholder "Opišite šta sve treba da se preveze i koliko toga ima."]


Unknown end tag for &lt;/div&gt;

</ br>

<div class="hide" id="hide4">
[textarea komentar x3 placeholder "Iskoristite ovo polje za sve što nije predviđeno, a smatrate da je važno za bolju procenu."]


Unknown end tag for &lt;/div&gt;

</ br>

<div class="hide" id="hide5">
[text* ime placeholder "Ime (obavezno)"]


Unknown end tag for &lt;/div&gt;

</ br>

<div class="hide" id="hide6">
[email* email placeholder "Validan Email (obavezno)"]


Unknown end tag for &lt;/div&gt;

</ br>

<div class="hide" id="hide7">
[tel telefon placeholder "Broj Telefona (opcionalno)"]


Unknown end tag for &lt;/div&gt;

</ br>

<div id="formButtons">[submit id:sendMessage class:contactForm "Izračunaj"]



Unknown end tag for &lt;/div&gt;




Unknown end tag for &lt;/div&gt;


```

# Header script inside < head > #
```

<!-- Add jquery script to support Conditional Forms-->
<script type="text/javascript" src="<?php echo get_stylesheet_directory_uri(); ?>/js/1.7.1/jquery-1.7.1.min.js">

Unknown end tag for &lt;/script&gt;



<script type="text/javascript" src="<?php echo get_stylesheet_directory_uri(); ?>/js/hidefieldsScript.js">

Unknown end tag for &lt;/script&gt;


```