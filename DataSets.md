## Transcription ##

The Voynichese project (VP) relies upon EVA transcriptions of the Voynich Manuscript available on the web - for instance, via the [Voynich Information Browser](http://voynich.freie-literatur.de/).

EVA is a popular transcription alphabet which uses characters A-Z to encode the symbols found in the Voynich Manuscript. Various such transcription alphabets are available, which often differ in the way that strokes are organized into symbols.

In the VP, the following lowercase EVA characters are used:

`a,c,d,e,f,g,h,i,k,l,m,n,o,p,q,r,s,t,v,x,y,z`

Additionally the `*` character is used to represent a set of one or more EVA characters.

See the [Credits & Copyright section](CreditsAndCopyright.md) for information on EVA and related transcriptions.

## Spatial Bindings ##

The VP uses an enhanced version of an EVA transcription in which transcribed words are bound to the area of the manuscript from which they were derived.

The following image depicts the bindings for folio 68V1.

![http://wiki.voynichese.googlecode.com/git/mapper.png](http://wiki.voynichese.googlecode.com/git/mapper.png)

Each blue region corresponds to a transcribed word, with position and dimensions matching the folio area that contains the associated symbols.

In the image, the yellow box indicates the folio's minimum content area whereas the green box corresponds to the selected viewport area.

The viewport area is an area of variable size that encompasses the majority of the folio's contents while retaining the standard aspect ratio of 1:1.4142. In the VP, the viewport area is used to trim the various folio images to fit specific width and height values.

Note that, as much as possible, the viewport area should contain the folio's minimum content area and prioritize text over images. In the VP, the following folios currently have text content outside the assigned viewport area due to their irregular size:

`f68r3, f68v3, f70r2, f70v2, f72r3, f72v3, f89r2, f89v2, f101r1, f101v2`

## Data Quality ##

The quality of a transcription may be determined by the number of transcription errors originating from data that's not subject to interpretation. For example, the EVA "d" character, which represents the Voynich symbol that resembles the numeral "8", is easily identified in the text. As such, a transcription wherein a portion of the "8" symbols are encoded as "d" while others are transcribed as "b", has low data quality. Consistency is important.

On the other hand, certain properties of the text must rely upon the transcription author's best judgement. Word boundaries are an example of this because different factors may contribute to longer or shorter spacing between blocks of symbols.

The semi-automated process that was used to bind transcribed words to folio areas indicates that there are some transcription errors of the first class - estimated at less than 1%. Transcription errors of the second class are more difficult to quantify though it is true that in some cases it is apparent that a longer word was transcribed as two or more shorter words.

You are therefore encouraged to use your judgement when performing your own analysis of the text. Additionally, you may use the [bug tracking](https://code.google.com/p/voynichese/issues/entry) feature of the project site to request corrections.

## Download ##

The VP's EVA based transcription, with corresponding spatial data, is available for download as a collection of XML files, under the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0):

[Download enhanced transcription](http://www.voynichese.com/1/data/folio/voynichese_data.zip)

The XML data for each folio specifies the coordinates, dimensions and contents for each transcribed word, as well as the folio's corresponding width and height, in the following format:

```
<?xml version="1.0" encoding="UTF-8"?>
<!--
    Copyright (C) 2014 The Voynichese Project

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

         http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
-->
<folio name="f1r" wordCount="210" width="1090" height="1500">
  <word index="0" x="97" y="128" width="106" height="96">fachys</word>
  <word index="1" x="225" y="164" width="58" height="61">ykal</word>
  <word index="2" x="299" y="182" width="25" height="26">ar</word>
  <word index="3" x="335" y="161" width="79" height="48">ataiin</word>
  <word index="4" x="434" y="177" width="55" height="28">shol</word>
  <word index="5" x="507" y="168" width="56" height="35">shory</word>
  <word index="6" x="592" y="158" width="88" height="49">cthres</word>
  <word index="7" x="687" y="195" width="17" height="27">y</word>
  <word index="8" x="712" y="154" width="40" height="53">kor</word>
  <word index="9" x="763" y="169" width="91" height="51">sholdy</word>
  <word index="10" x="112" y="225" width="65" height="35">sory</word>
  <word index="11" x="193" y="217" width="70" height="34">ckhar</word>
  <word index="12" x="274" y="226" width="31" height="23">or</word>
  <word index="13" x="309" y="240" width="15" height="21">y</word>
  <word index="14" x="337" y="211" width="48" height="32">kair</word>
  <word index="15" x="398" y="206" width="101" height="35">chtaiin</word>
  <word index="16" x="512" y="208" width="59" height="27">shar</word>
  <word index="17" x="578" y="214" width="39" height="27">are</word>
  <word index="18" x="629" y="207" width="82" height="35">cthar</word>
  <word index="19" x="721" y="208" width="82" height="36">cthar</word>
  <word index="20" x="808" y="224" width="48" height="19">dan</word>
  <word index="21" x="91" y="260" width="110" height="27">syaiir</word>
  <word index="22" x="210" y="249" width="72" height="40">sheky</word>
  <word index="23" x="295" y="261" width="31" height="21">or</word>
  <word index="24" x="333" y="243" width="84" height="48">ykaiin</word>
  <word index="25" x="432" y="241" width="61" height="36">shod</word>
  <word index="26" x="505" y="241" width="110" height="44">cthoary</word>
  <word index="27" x="632" y="242" width="65" height="34">cthes</word>
  <word index="28" x="714" y="254" width="100" height="26">daraiin</word>
  <word index="29" x="822" y="256" width="26" height="34">sa</word>
  <word index="30" x="112" y="297" width="65" height="24">ooiin</word>
  <word index="31" x="188" y="283" width="69" height="51">oteey</word>
  <word index="32" x="272" y="284" width="73" height="31">oteos</word>
  <word index="33" x="351" y="279" width="101" height="36">roloty</word>
  <word index="34" x="469" y="274" width="90" height="41">cthar</word>
  <word index="35" x="568" y="286" width="73" height="29">daiin</word>
  <word index="36" x="651" y="276" width="83" height="35">otaiin</word>
  <word index="37" x="743" y="290" width="33" height="19">or</word>
  <word index="38" x="786" y="281" width="64" height="30">okan</word>
  <word index="39" x="120" y="328" width="47" height="28">dair</word>
  <word index="40" x="168" y="346" width="13" height="26">y</word>
  <word index="41" x="198" y="326" width="67" height="29">chear</word>
  <word index="42" x="279" y="315" width="93" height="42">cthaiin</word>
  <word index="43" x="380" y="315" width="81" height="34">cphar</word>
  <word index="44" x="475" y="312" width="92" height="34">cfhaiin</word>
  <word index="45" x="711" y="319" width="128" height="39">ydaraishy</word>
  <word index="46" x="196" y="393" width="51" height="35">odar</word>
  <word index="47" x="264" y="401" width="20" height="27">o</word>
  <word index="48" x="284" y="416" width="14" height="18">y</word>
  <word index="49" x="309" y="398" width="52" height="31">shol</word>
  <word index="50" x="369" y="372" width="83" height="62">cphoy</word>
  <word index="51" x="468" y="400" width="68" height="28">oydar</word>
  <word index="52" x="556" y="398" width="22" height="29">sh</word>
  <word index="53" x="598" y="399" width="17" height="28">s</word>
  <word index="54" x="618" y="373" width="106" height="60">cfhoaiin</word>
  <word index="55" x="739" y="399" width="98" height="32">shodary</word>
  <word index="56" x="114" y="444" width="62" height="44">yshey</word>
  <word index="57" x="192" y="437" width="67" height="37">shody</word>
  <word index="58" x="275" y="429" width="76" height="38">okchoy</word>
  <word index="59" x="365" y="430" width="79" height="40">otchol</word>
  <word index="60" x="456" y="429" width="93" height="45">chocthy</word>
  <word index="61" x="564" y="440" width="69" height="43">oschy</word>
  <word index="62" x="646" y="445" width="64" height="23">dain</word>
  <word index="63" x="719" y="441" width="63" height="26">chor</word>
  <word index="64" x="794" y="430" width="48" height="33">kos</word>
  <word index="65" x="112" y="488" width="57" height="21">daiin</word>
  <word index="66" x="182" y="474" width="65" height="31">shos</word>
  <word index="67" x="259" y="460" width="73" height="55">cfhol</word>
  <word index="68" x="344" y="471" width="63" height="43">shody</word>
  <word index="69" x="630" y="479" width="53" height="21">dain</word>
  <word index="70" x="693" y="474" width="33" height="27">os</word>
  <word index="71" x="729" y="468" width="80" height="38">teody</word>
  <word index="72" x="150" y="577" width="68" height="35">ydain</word>
  <word index="73" x="229" y="546" width="118" height="55">cphesaiin</word>
  <word index="74" x="367" y="585" width="26" height="20">ol</word>
  <word index="75" x="393" y="581" width="16" height="20">s</word>
  <word index="76" x="418" y="557" width="65" height="45">cphey</word>
  <word index="77" x="503" y="561" width="81" height="46">ytain</word>
  <word index="78" x="598" y="576" width="90" height="44">shoshy</word>
  <word index="79" x="688" y="569" width="155" height="39">cphodales</word>
  <word index="80" x="109" y="614" width="78" height="41">oksho</word>
  <word index="81" x="200" y="604" width="71" height="48">kshoy</word>
  <word index="82" x="282" y="601" width="99" height="38">otairin</word>
  <word index="83" x="394" y="604" width="79" height="37">oteol</word>
  <word index="84" x="493" y="602" width="65" height="36">okan</word>
  <word index="85" x="568" y="607" width="107" height="36">shodain</word>
  <word index="86" x="688" y="608" width="76" height="51">sckhey</word>
  <word index="87" x="775" y="619" width="62" height="20">daiin</word>
  <word index="88" x="110" y="656" width="65" height="35">shoy</word>
  <word index="89" x="189" y="641" width="76" height="50">ckhey</word>
  <word index="90" x="281" y="642" width="96" height="34">kodaiin</word>
  <word index="91" x="391" y="641" width="56" height="44">cphy</word>
  <word index="92" x="447" y="641" width="137" height="42">cphodaiils</word>
  <word index="93" x="592" y="646" width="63" height="43">cthey</word>
  <word index="94" x="668" y="651" width="49" height="28">she</word>
  <word index="95" x="731" y="655" width="93" height="24">oldain</word>
  <word index="96" x="834" y="654" width="13" height="18">d</word>
  <word index="97" x="110" y="691" width="50" height="22">dain</word>
  <word index="98" x="172" y="691" width="48" height="18">oiin</word>
  <word index="99" x="238" y="694" width="55" height="17">chol</word>
  <word index="100" x="307" y="688" width="80" height="22">odaiin</word>
  <word index="101" x="402" y="689" width="97" height="20">chodain</word>
  <word index="102" x="516" y="690" width="50" height="26">chdy</word>
  <word index="103" x="584" y="684" width="75" height="29">okain</word>
  <word index="104" x="668" y="691" width="52" height="23">dan</word>
  <word index="105" x="733" y="681" width="62" height="45">cthy</word>
  <word index="106" x="813" y="674" width="42" height="34">kod</word>
  <word index="107" x="109" y="722" width="60" height="23">daiin</word>
  <word index="108" x="181" y="709" width="85" height="45">shckhey</word>
  <word index="109" x="284" y="711" width="81" height="32">ckeor</word>
  <word index="110" x="372" y="716" width="63" height="28">chor</word>
  <word index="111" x="448" y="716" width="60" height="50">shey</word>
  <word index="112" x="527" y="710" width="46" height="41">kol</word>
  <word index="113" x="580" y="730" width="51" height="17">chol</word>
  <word index="114" x="647" y="732" width="50" height="20">chol</word>
  <word index="115" x="706" y="711" width="46" height="35">kor</word>
  <word index="116" x="762" y="734" width="50" height="13">chal</word>
  <word index="117" x="110" y="747" width="39" height="27">sho</word>
  <word index="118" x="159" y="754" width="53" height="17">chol</word>
  <word index="119" x="225" y="748" width="97" height="23">shodan</word>
  <word index="120" x="340" y="741" width="65" height="43">kshy</word>
  <word index="121" x="415" y="744" width="57" height="36">kchy</word>
  <word index="122" x="492" y="751" width="49" height="23">dor</word>
  <word index="123" x="553" y="749" width="118" height="25">chodaiin</word>
  <word index="124" x="691" y="747" width="39" height="28">sho</word>
  <word index="125" x="740" y="744" width="88" height="35">kchom</word>
  <word index="126" x="112" y="787" width="61" height="25">ycho</word>
  <word index="127" x="180" y="771" width="79" height="34">tchey</word>
  <word index="128" x="275" y="771" width="105" height="33">chokain</word>
  <word index="129" x="394" y="775" width="56" height="27">sheo</word>
  <word index="130" x="451" y="768" width="90" height="39">pshol</word>
  <word index="131" x="560" y="786" width="73" height="24">dydyd</word>
  <word index="132" x="657" y="773" width="54" height="45">cthy</word>
  <word index="133" x="724" y="775" width="94" height="40">daicthy</word>
  <word index="134" x="111" y="803" width="49" height="48">yto</word>
  <word index="135" x="172" y="802" width="58" height="36">shol</word>
  <word index="136" x="245" y="802" width="42" height="34">she</word>
  <word index="137" x="299" y="804" width="114" height="39">kodshey</word>
  <word index="138" x="429" y="801" width="109" height="50">cphealy</word>
  <word index="139" x="564" y="814" width="89" height="31">dasain</word>
  <word index="140" x="672" y="821" width="58" height="24">dain</word>
  <word index="141" x="741" y="814" width="100" height="39">ckhyds</word>
  <word index="142" x="111" y="845" width="68" height="26">dchar</word>
  <word index="143" x="189" y="834" width="122" height="39">shcthaiin</word>
  <word index="144" x="327" y="842" width="79" height="29">okaiir</word>
  <word index="145" x="408" y="852" width="53" height="30">chey</word>
  <word index="146" x="477" y="854" width="57" height="45">rchy</word>
  <word index="147" x="538" y="841" width="95" height="47">potol</word>
  <word index="148" x="647" y="842" width="92" height="44">cthols</word>
  <word index="149" x="749" y="851" width="91" height="37">dlocta</word>
  <word index="150" x="114" y="871" width="62" height="32">shok</word>
  <word index="151" x="180" y="875" width="57" height="28">chor</word>
  <word index="152" x="252" y="890" width="0" height="22">chey</word>
  <word index="153" x="324" y="881" width="54" height="26">dain</word>
  <word index="154" x="393" y="874" width="65" height="55">ckhey</word>
  <word index="155" x="674" y="887" width="60" height="36">otol</word>
  <word index="156" x="747" y="898" width="78" height="33">daiiin</word>
  <word index="157" x="99" y="926" width="149" height="79">cpho</word>
  <word index="158" x="155" y="980" width="77" height="33">shaiin</word>
  <word index="159" x="246" y="969" width="98" height="47">shokcheey</word>
  <word index="160" x="359" y="1000" width="0" height="27">chol</word>
  <word index="161" x="419" y="962" width="122" height="64">tshodeesy</word>
  <word index="162" x="558" y="992" width="46" height="39">shey</word>
  <word index="163" x="604" y="976" width="90" height="61">pydeey</word>
  <word index="164" x="704" y="1016" width="35" height="26">chy</word>
  <word index="165" x="749" y="1006" width="26" height="26">ro</word>
  <word index="166" x="782" y="1004" width="43" height="30">d</word>
  <word index="167" x="104" y="1018" width="64" height="34">doin</word>
  <word index="168" x="180" y="1032" width="51" height="18">chol</word>
  <word index="169" x="244" y="1030" width="52" height="22">dain</word>
  <word index="170" x="308" y="1016" width="68" height="35">cthal</word>
  <word index="171" x="388" y="1031" width="47" height="22">dar</word>
  <word index="172" x="447" y="1028" width="73" height="27">shear</word>
  <word index="173" x="534" y="1022" width="63" height="41">kaiin</word>
  <word index="174" x="608" y="1040" width="45" height="25">dar</word>
  <word index="175" x="666" y="1037" width="49" height="36">shey</word>
  <word index="176" x="727" y="1032" width="72" height="32">cthar</word>
  <word index="177" x="102" y="1063" width="69" height="17">choo</word>
  <word index="178" x="181" y="1050" width="51" height="34">kaiin</word>
  <word index="179" x="246" y="1057" width="84" height="27">shoaiin</word>
  <word index="180" x="348" y="1052" width="62" height="34">okol</word>
  <word index="181" x="421" y="1067" width="67" height="25">daiin</word>
  <word index="182" x="494" y="1058" width="49" height="37">far</word>
  <word index="183" x="555" y="1063" width="73" height="37">cthol</word>
  <word index="184" x="642" y="1077" width="55" height="24">daiin</word>
  <word index="185" x="712" y="1067" width="107" height="38">ctholdar</word>
  <word index="186" x="100" y="1100" width="65" height="24">ycheey</word>
  <word index="187" x="176" y="1084" width="57" height="35">okay</word>
  <word index="188" x="258" y="1083" width="39" height="36">oky</word>
  <word index="189" x="310" y="1092" width="57" height="25">daiin</word>
  <word index="190" x="384" y="1086" width="85" height="44">okchey</word>
  <word index="191" x="479" y="1091" width="99" height="41">kokaiin</word>
  <word index="192" x="589" y="1117" width="90" height="22">chol</word>
  <word index="193" x="689" y="1105" width="73" height="36">kchy</word>
  <word index="194" x="772" y="1120" width="38" height="18">dal</word>
  <word index="195" x="101" y="1125" width="55" height="23">deeo</word>
  <word index="196" x="173" y="1126" width="75" height="36">shody</word>
  <word index="197" x="267" y="1119" width="73" height="36">koshey</word>
  <word index="198" x="356" y="1120" width="60" height="40">cthy</word>
  <word index="199" x="435" y="1130" width="91" height="33">okchey</word>
  <word index="200" x="538" y="1132" width="56" height="45">keey</word>
  <word index="201" x="605" y="1139" width="55" height="43">keey</word>
  <word index="202" x="666" y="1154" width="46" height="27">dal</word>
  <word index="203" x="724" y="1141" width="80" height="35">chtor</word>
  <word index="204" x="100" y="1163" width="44" height="15">eo</word>
  <word index="205" x="174" y="1166" width="58" height="22">chol</word>
  <word index="206" x="246" y="1155" width="65" height="31">chok</word>
  <word index="207" x="318" y="1157" width="76" height="45">choty</word>
  <word index="208" x="410" y="1160" width="80" height="44">chotey</word>
  <word index="209" x="689" y="1186" width="85" height="27">dchaiin</word>
</folio>
```