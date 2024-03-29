# Common Turkic Alphabet

[wikipedia'en / Common Turkic Alphabet](https://en.wikipedia.org/wiki/Common_Turkic_Alphabet)

Common Turkic Alphabet without "**İ, ı**" (or pairs "**İ i, I ı**") letters  
<a href="https://github.com/2k1dmg/cta/blob/main/ru.md">ru</a>

<details>
  <summary>Links:</summary>
  
[The Turkish İ Problem and Why You Should Care](https://haacked.com/archive/2012/07/05/turkish-i-problem-and-why-you-should-care.aspx/)  
[Internationalization for Turkish: Dotted and Dotless Letter "I"](http://www.i18nguy.com/unicode/turkish-i18n.html)  
[Why does Unicode implement the Turkish I the way it does?](https://stackoverflow.com/questions/48067545/why-does-unicode-implement-the-turkish-i-the-way-it-does)
  
</details>

"**İ i**" replaced by "**I i**"  
"**I ı**"  replaced by "**Ī ī**"  
If something is found that is better than "**Ī ī**", then it will be replaced by it. Unfortunately, there are no good alternatives for "**I ı**" because the letter "**ı**" has a high frequency. And the new one should not be with a diacritical mark.  
One of the solutions is to create a new pair "**ᛚ ı**" of lowercase letters from which will look like "**ı**", capital on the rune "[**ᛚ**](https://en.wikipedia.org/wiki/Laguz)". Or both are similar to the rune.  Instead of the rune "**ᛚ**", there may be another similar one, but which differs from the Latin "**I**".  
Examples: KᛚRK, kırk; KᛚŞ, kış  
Replace two existing unused letters of [Latin script in Unicode](https://en.wikipedia.org/wiki/Latin_script_in_Unicode). For example "**Ý ý Ỳ ỳ Ŷ ŷ Ÿ ÿ Ỹ ỹ Ẏ ẏ Ȳ ȳ Ỷ ỷ Ỵ ỵ Ɏ ɏ Ƴ ƴ Ỿ ỿ**" letters.  
old fonts: KŶRK, kŷrk; KŶŞ, kŷş  
old fonts: KȲRK, kȳrk; KȲŞ, kȳş  
new fonts: KᛚRK, kırk; KᛚŞ, kış  
Replacing existing ones rather than adding new ones is better for backward compatibility. If the font does not contain these new letters, it is better to show the old ones than nothing.

Or just use one of these "**Í í, Ì ì, Ĭ ĭ, Î î, Ǐ ǐ, Ïï, Ĩĩ, Į į, Ī ī**" or "**Ý ý Ỳ ỳ Ŷ ŷ Ÿ ÿ Ỹ ỹ Ẏ ẏ Ȳ ȳ Ỷ ỷ Ỵ ỵ Ɏ ɏ Ƴ ƴ Ỿ ỿ**" or "**Ƽ ƽ Ƨ ƨ Ƅ ƅ Ɣ ɣ Ƕ ƕ Ƣ ƣ**" or "**Ɩ ɩ**" and not replace anything. "**Ī ī**" can be replaced for example by "**Ǐ ǐ**" or "**Ì ì**" or "**Ỿ ỿ**" or "**Ƨ ƨ**" if it looks better in the text.

You can also use these letters:  
"**Ā ā, Ō ō, Ū ū**" instead of "**Ä ä, Ö ö, Ü ü**"  
"**Î î**" instead of "**Ī ī**"  
"**Ă Ĕ Ĭ Ŏ Ŭ ă ĕ ĭ ŏ ŭ**" instead of "**Â Ê Î Ô Û â ê î ô û**".  

<table>
   <tbody>
      <tr>
         <th colspan="52">Common Turkic Alphabet</th>
      </tr>
      <tr>
         <th>Upper Case</th>
         <td>A</td>
         <td>Ä</td>
         <td>B</td>
         <td>C</td>
         <td>Ç</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>Ğ</td>
         <td>H</td>
         <td>I</td>
         <td>Ī</td>
         <td>J</td>
         <td>K</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>Ñ</td>
         <td>O</td>
         <td>Ö</td>
         <td>P</td>
         <td>Q</td>
         <td>R</td>
         <td>S</td>
         <td>Ş</td>
         <td>T</td>
         <td>U</td>
         <td>Ü</td>
         <td>V</td>
         <td>W</td>
         <td>X</td>
         <td>Y</td>
         <td>Z</td>
      </tr>
      <tr>
         <th>Lower Case</th>
         <td>a</td>
         <td>ä</td>
         <td>b</td>
         <td>c</td>
         <td>ç</td>
         <td>d</td>
         <td>e</td>
         <td>f</td>
         <td>g</td>
         <td>ğ</td>
         <td>h</td>
         <td>i</td>
         <td>ī</td>
         <td>j</td>
         <td>k</td>
         <td>l</td>
         <td>m</td>
         <td>n</td>
         <td>ñ</td>
         <td>o</td>
         <td>ö</td>
         <td>p</td>
         <td>q</td>
         <td>r</td>
         <td>s</td>
         <td>ş</td>
         <td>t</td>
         <td>u</td>
         <td>ü</td>
         <td>v</td>
         <td>w</td>
         <td>x</td>
         <td>y</td>
         <td>z</td>
      </tr>
      <tr>
         <th>IPA</th>
         <td>ɑ</td>
         <td>æ</td>
         <td>b</td>
         <td>dʒ</td>
         <td>tʃ</td>
         <td>d</td>
         <td>e</td>
         <td>f</td>
         <td>g</td>
         <td>ɣ</td>
         <td>h</td>
         <td>i</td>
         <td>ɯ</td>
         <td>ʒ</td>
         <td>c, k</td>
         <td>l</td>
         <td>m</td>
         <td>n</td>
         <td>ŋ</td>
         <td>o</td>
         <td>ø</td>
         <td>p</td>
         <td>q</td>
         <td>r</td>
         <td>s</td>
         <td>ʃ</td>
         <td>t</td>
         <td>u</td>
         <td>y</td>
         <td>v</td>
         <td>w</td>
         <td>x</td>
         <td>j</td>
         <td>z</td>
      </tr>
   </tbody>
</table>

### Main
`A Ä B C Ç D E F G Ğ H I Ī J K L M N Ñ O Ö P Q R S Ş T U Ü V W X Y Z`  
`a ä b c ç d e f g ğ h i ī j k l m n ñ o ö p q r s ş t u ü v w x y z`

### Additional
`Ś Ź Ţ Ə Ō`  
`ś ź ţ ə ō`

### Extended
`Â Ê Î Ô Û`  
`â ê î ô û`

**Jj** = /ʒ/<br>
**Jj** = /d͡ʒ/ often with "Jj" first letter in the non turkic words (examples: Japonya, Jamaika)

<table>
   <tbody>
      <tr>
         <th colspan="52">Turkic languages in alphabets based on the Common Turkic Alphabet</th>
      </tr>
      <tr>
         <th>Common</th>
         <td>A</td>
         <td>Ä</td>
         <td>B</td>
         <td>C</td>
         <td>Ç</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>Ğ</td>
         <td>H</td>
         <td>X</td>
         <td>I</td>
         <td>Ī</td>
         <td>J</td>
         <td>K</td>
         <td>Q</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>Ñ</td>
         <td>O</td>
         <td>Ö</td>
         <td>P</td>
         <td>R</td>
         <td>S</td>
         <td>Ś</td>
         <td>Ş</td>
         <td>T</td>
         <td>Ţ</td>
         <td>U</td>
         <td>Ü</td>
         <td>V</td>
         <td>W</td>
         <td>Y</td>
         <td>Z</td>
         <td>Ź</td>
      </tr>
      <tr>
         <th>ASCII<a href="https://github.com/2k1dmg/cta/blob/main/ASCII/ASCII.md">*</a></th>
         <td>A</td>
         <td>AE/A</td>
         <td>B</td>
         <td>J</td>
         <td>CH</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>GH/G</td>
         <td>H/KH</td>
         <td>H/KH</td>
         <td>I</td>
         <td>Y</td>
         <td>ZH/J</td>
         <td>K</td>
         <td>Q/K</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>NG</td>
         <td>O</td>
         <td>OE/O</td>
         <td>P</td>
         <td>R</td>
         <td>S</td>
         <td>TH</td>
         <td>SH</td>
         <td>T</td>
         <td>C</td>
         <td>U</td>
         <td>UE/U</td>
         <td>V</td>
         <td>W</td>
         <td>Y</td>
         <td>Z</td>
         <td>DH</td>
      </tr>
      <tr>
         <th>Cyrillic</th>
         <td>А</td>
         <td>Ә</td>
         <td>Б</td>
         <td>Җ</td>
         <td>Ч</td>
         <td>Д</td>
         <td>Е</td>
         <td>Ф</td>
         <td>Г</td>
         <td>Ғ</td>
         <td>Һ, Ҳ</td>
         <td>Х</td>
         <td>И</td>
         <td>Ы</td>
         <td>Ж</td>
         <td>К</td>
         <td>Ҡ, Қ</td>
         <td>Л</td>
         <td>М</td>
         <td>Н</td>
         <td>Ң</td>
         <td>О</td>
         <td>Ө</td>
         <td>П</td>
         <td>Р</td>
         <td>С</td>
         <td>Ҫ</td>
         <td>Ш</td>
         <td>Т</td>
         <td>Ц</td>
         <td>У</td>
         <td>Ү</td>
         <td>В</td>
         <td>Ў</td>
         <td>Й</td>
         <td>З</td>
         <td>Ҙ</td>
      </tr>
      <tr>
         <th>Turkish</th>
         <td>A</td>
         <td>-</td>
         <td>B</td>
         <td>C</td>
         <td>Ç</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>Ğ</td>
         <td>H</td>
         <td>-</td>
         <td>I</td>
         <td>Ī</td>
         <td>J</td>
         <td>K</td>
         <td>-</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>-</td>
         <td>O</td>
         <td>Ö</td>
         <td>P</td>
         <td>R</td>
         <td>S</td>
         <td>-</td>
         <td>Ş</td>
         <td>T</td>
         <td>-</td>
         <td>U</td>
         <td>Ü</td>
         <td>V</td>
         <td>-</td>
         <td>Y</td>
         <td>Z</td>
         <td>-</td>
      </tr>
      <tr>
         <th>Azerbaijani<a href="https://github.com/2k1dmg/cta/blob/main/Azerbaijani/Azerbaijani.md">*</a></th>
         <td>A</td>
         <td>Ä(Ə)</td>
         <td>B</td>
         <td>C</td>
         <td>Ç</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>Ğ</td>
         <td>H</td>
         <td>X</td>
         <td>I</td>
         <td>Ī</td>
         <td>J</td>
         <td>K</td>
         <td>G/Q</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>-</td>
         <td>O</td>
         <td>Ö</td>
         <td>P</td>
         <td>R</td>
         <td>S</td>
         <td>-</td>
         <td>Ş</td>
         <td>T</td>
         <td>-</td>
         <td>U</td>
         <td>Ü</td>
         <td>V</td>
         <td>-</td>
         <td>Y</td>
         <td>Z</td>
         <td>-</td>
      </tr>
      <tr>
         <th>Turkmen</th>
         <td>A</td>
         <td>Ä</td>
         <td>B</td>
         <td>C</td>
         <td>Ç</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>Ğ</td>
         <td>H</td>
         <td>-</td>
         <td>I</td>
         <td>Ī</td>
         <td>J</td>
         <td>K</td>
         <td>-</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>Ñ</td>
         <td>O</td>
         <td>Ö</td>
         <td>P</td>
         <td>R</td>
         <td>S</td>
         <td>-</td>
         <td>Ş</td>
         <td>T</td>
         <td>-</td>
         <td>U</td>
         <td>Ü</td>
         <td>V</td>
         <td>-</td>
         <td>Y</td>
         <td>Z</td>
         <td>-</td>
      </tr>
      <tr>
         <th>Gagauz</th>
         <td>A</td>
         <td>Ä</td>
         <td>B</td>
         <td>C</td>
         <td>Ç</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>-</td>
         <td>H</td>
         <td>-</td>
         <td>I</td>
         <td>Ī</td>
         <td>J</td>
         <td>K</td>
         <td>-</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>-</td>
         <td>O</td>
         <td>Ö</td>
         <td>P</td>
         <td>R</td>
         <td>S</td>
         <td>-</td>
         <td>Ş</td>
         <td>T</td>
         <td>Ţ</td>
         <td>U</td>
         <td>Ü</td>
         <td>V</td>
         <td>-</td>
         <td>Y</td>
         <td>Z</td>
         <td>-</td>
      </tr>
      <tr>
         <th>Barsilian<a href="https://github.com/2k1dmg/cta/blob/main/Barsilian/Barsilian.md">*</a></th>
         <td>A</td>
         <td>Ä</td>
         <td>B</td>
         <td>C</td>
         <td>Ç</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>Ğ</td>
         <td>H</td>
         <td>-</td>
         <td>I</td>
         <td>Ī</td>
         <td>J</td>
         <td>K</td>
         <td>-</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>Ñ</td>
         <td>O</td>
         <td>Ö</td>
         <td>P</td>
         <td>R</td>
         <td>S</td>
         <td>-</td>
         <td>Ş</td>
         <td>T</td>
         <td>-</td>
         <td>U</td>
         <td>Ü</td>
         <td>V</td>
         <td>W</td>
         <td>Y</td>
         <td>Z</td>
         <td>-</td>
      </tr>
      <tr>
         <th>Crimean Tatar</th>
         <td>A</td>
         <td>-</td>
         <td>B</td>
         <td>C</td>
         <td>Ç</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>Ğ</td>
         <td>H</td>
         <td>-</td>
         <td>I</td>
         <td>Ī</td>
         <td>J</td>
         <td>K</td>
         <td>Q</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>Ñ</td>
         <td>O</td>
         <td>Ö</td>
         <td>P</td>
         <td>R</td>
         <td>S</td>
         <td>-</td>
         <td>Ş</td>
         <td>T</td>
         <td>-</td>
         <td>U</td>
         <td>Ü</td>
         <td>V</td>
         <td>-</td>
         <td>Y</td>
         <td>Z</td>
         <td>-</td>
      </tr>
      <tr>
         <th>Tatar<a href="https://github.com/2k1dmg/cta/blob/main/Tatar/Tatar.md">*</a></th>
         <td>A</td>
         <td>Ä(Ə)</td>
         <td>B</td>
         <td>C</td>
         <td>Ç</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>Ğ</td>
         <td>H</td>
         <td>X</td>
         <td>I</td>
         <td>Ī</td>
         <td>J</td>
         <td>K</td>
         <td>Q</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>Ñ</td>
         <td>O</td>
         <td>Ö</td>
         <td>P</td>
         <td>R</td>
         <td>S</td>
         <td>-</td>
         <td>Ş</td>
         <td>T</td>
         <td>-</td>
         <td>U</td>
         <td>Ü</td>
         <td>V</td>
         <td>W</td>
         <td>Y</td>
         <td>Z</td>
         <td>-</td>
      </tr>
      <tr>
         <th>Bashkir</th>
         <td>A</td>
         <td>Ä(Ə)</td>
         <td>B</td>
         <td>-</td>
         <td>Ç</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>Ğ</td>
         <td>H</td>
         <td>X</td>
         <td>I</td>
         <td>Ī</td>
         <td>J</td>
         <td>K</td>
         <td>Q</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>Ñ</td>
         <td>O</td>
         <td>Ö</td>
         <td>P</td>
         <td>R</td>
         <td>S</td>
         <td>Ś</td>
         <td>Ş</td>
         <td>T</td>
         <td>-</td>
         <td>U</td>
         <td>Ü</td>
         <td>V</td>
         <td>W</td>
         <td>Y</td>
         <td>Z</td>
         <td>Ź</td>
      </tr>
      <tr>
         <th>Kumyk</th>
         <td>A</td>
         <td>Ä</td>
         <td>B</td>
         <td>C</td>
         <td>Ç</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>Ğ</td>
         <td>H</td>
         <td>X</td>
         <td>I</td>
         <td>Ī</td>
         <td>J</td>
         <td>K</td>
         <td>Q</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>Ñ</td>
         <td>O</td>
         <td>Ö</td>
         <td>P</td>
         <td>R</td>
         <td>S</td>
         <td>-</td>
         <td>Ş</td>
         <td>T</td>
         <td>Ţ</td>
         <td>U</td>
         <td>Ü</td>
         <td>V</td>
         <td>W</td>
         <td>Y</td>
         <td>Z</td>
         <td>-</td>
      </tr>
      <tr>
         <th>Karachay-Balkar</th>
         <td>A</td>
         <td>-</td>
         <td>B</td>
         <td>C</td>
         <td>Ç</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>Ğ</td>
         <td>H</td>
         <td>-</td>
         <td>I</td>
         <td>Ī</td>
         <td>J</td>
         <td>K</td>
         <td>Q</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>Ñ</td>
         <td>O</td>
         <td>Ö</td>
         <td>P</td>
         <td>R</td>
         <td>S</td>
         <td>-</td>
         <td>Ş</td>
         <td>T</td>
         <td>Ţ</td>
         <td>U</td>
         <td>Ü</td>
         <td>V</td>
         <td>W</td>
         <td>Y</td>
         <td>Z</td>
         <td>-</td>
      </tr>
      <tr>
         <th>Kazakh</th>
         <td>A</td>
         <td>Ä</td>
         <td>B</td>
         <td>-</td>
         <td>Ç</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>Ğ</td>
         <td>H</td>
         <td>-</td>
         <td>I</td>
         <td>Ī</td>
         <td>J</td>
         <td>K</td>
         <td>Q</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>Ñ</td>
         <td>O</td>
         <td>Ö</td>
         <td>P</td>
         <td>R</td>
         <td>S</td>
         <td>-</td>
         <td>Ş</td>
         <td>T</td>
         <td>-</td>
         <td>U</td>
         <td>Ü</td>
         <td>V</td>
         <td>W</td>
         <td>Y</td>
         <td>Z</td>
         <td>-</td>
      </tr>
      <tr>
         <th>Nogai</th>
         <td>A</td>
         <td>Ä</td>
         <td>B</td>
         <td>C</td>
         <td>Ç</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>-</td>
         <td>H</td>
         <td>-</td>
         <td>I</td>
         <td>Ī</td>
         <td>J</td>
         <td>K</td>
         <td>-</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>Ñ</td>
         <td>O</td>
         <td>Ö</td>
         <td>P</td>
         <td>R</td>
         <td>S</td>
         <td>-</td>
         <td>Ş</td>
         <td>T</td>
         <td>Ţ</td>
         <td>U</td>
         <td>Ü</td>
         <td>V</td>
         <td>W</td>
         <td>Y</td>
         <td>Z</td>
         <td>-</td>
      </tr>
      <tr>
         <th>Kyrgyz</th>
         <td>A</td>
         <td>Ä</td>
         <td>B</td>
         <td>C</td>
         <td>Ç</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>Ğ</td>
         <td>H</td>
         <td>-</td>
         <td>I</td>
         <td>Ī</td>
         <td>J</td>
         <td>K</td>
         <td>Q</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>Ñ</td>
         <td>O</td>
         <td>Ö</td>
         <td>P</td>
         <td>R</td>
         <td>S</td>
         <td>-</td>
         <td>Ş</td>
         <td>T</td>
         <td>-</td>
         <td>U</td>
         <td>Ü</td>
         <td>V</td>
         <td>W</td>
         <td>Y</td>
         <td>Z</td>
         <td>-</td>
      </tr>
      <tr>
         <th>Uzbek</th>
         <td>A</td>
         <td>-</td>
         <td>B</td>
         <td>-</td>
         <td>Ç</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>Ğ</td>
         <td>H</td>
         <td>X</td>
         <td>I</td>
         <td>-</td>
         <td>J</td>
         <td>K</td>
         <td>Q</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>Ñ</td>
         <td>O</td>
         <td>Ö(Ō)</td>
         <td>P</td>
         <td>R</td>
         <td>S</td>
         <td>-</td>
         <td>Ş</td>
         <td>T</td>
         <td>-</td>
         <td>U</td>
         <td>-</td>
         <td>V</td>
         <td>-</td>
         <td>Y</td>
         <td>Z</td>
         <td>-</td>
      </tr>
      <tr>
         <th>Uyghur</th>
         <td>A</td>
         <td>Ä(Ə)</td>
         <td>B</td>
         <td>C</td>
         <td>Ç</td>
         <td>D</td>
         <td>E</td>
         <td>F</td>
         <td>G</td>
         <td>Ğ</td>
         <td>H</td>
         <td>X</td>
         <td>I</td>
         <td>Ī</td>
         <td>J</td>
         <td>K</td>
         <td>Q</td>
         <td>L</td>
         <td>M</td>
         <td>N</td>
         <td>Ñ</td>
         <td>O</td>
         <td>Ö</td>
         <td>P</td>
         <td>R</td>
         <td>S</td>
         <td>-</td>
         <td>Ş</td>
         <td>T</td>
         <td>-</td>
         <td>U</td>
         <td>Ü</td>
         <td>V</td>
         <td>W</td>
         <td>Y</td>
         <td>Z</td>
         <td>-</td>
      </tr>
   </tbody>
</table>

_ToDo: add other turkic alphabets_

- (?) In the Tatar and Bashkir alphabets, the letter "Ää" was replaced by "Əə" because of the high frequency of this letter in these languages.
- In the Azerbaijani languages, the letters "Qq" is written only with soft vowels or soft words in other cases is written "Gg". For greater clarity, you can replace "Qq" with "Ĝĝ".
- Kazakh alphabet based on "Qazaq Grammar" with "Şş" instead of "Cc".
- Kyrgyz alphabet [based on](https://www.qyrgyz.com/post/kakoy-budet-kyrgyzskaya-latinitsa)".

## Proposal
In languages that use "**q**, **ğ**" (hard **k** and **g**) and "**x**" replace them with "**k**, **g**" and "**h**".  
"**q**, **ğ**" letters written only with soft vowels.  
Letters "**q**, **ğ**, **x**" use in phrase books and dictionaries for pronunciation help.

## Alternatives

### Main
`A Ā B C Ç D E F G Ğ H I Î J K L M N Ñ O Ō P Q R S Ş T U Ū V W X Y Z`  
`a ā b c ç d e f g ğ h i î j k l m n ñ o ō p q r s ş t u ū v w x y z`

`Ś Ź Ţ Ə`  
`ś ź ţ ə`

`Ă Ĕ Ĭ Ŏ Ŭ`  
`ă ĕ ĭ ŏ ŭ`

### Main + Ż ż [t͡s]
`A Ä B C Č D E F G Ğ H I Y Ž K L M N Ñ O Ö P R S Š T U Ü V W J Z Ż`  
`a ä b c č d e f g ğ h i y ž k l m n ñ o ö p r s š t u ü v w j z ż`  
The letter "h" after the consonants and the letter "i" is written as "ch". [letters q ğ x](#proposal)  
In most European alphabets, the sound ⟨j⟩ is written with the letter "j".

### Main (Ɩ ɩ = Ī ī)
`A Ä B C Ç D E F G Ğ H I Ɩ J K L M N Ñ O Ö P Q R S Ş T U Ü V W X Y Z`  
`a ä b c ç d e f g ğ h i ɩ j k l m n ñ o ö p q r s ş t u ü v w x y z`

### Main (Ì ì = Ī ī; Ā ā = Ä ä; Ō ō = Ö ö; Ū ū = Ü ü)
`A Ā B C Ç D E F G Ğ H I Ì J K L M N Ñ O Ō P Q R S Ş T U Ū V W X Y Z`  
`a ā b c ç d e f g ğ h i ì j k l m n ñ o ō p q r s ş t u ū v w x y z`

### Main (Ĩ ĩ = Ī ī; Ň ň = Ñ ñ)
`A Ä B C Ç D E F G Ğ H I Ĩ J K L M N Ň O Ö P Q R S Ş T U Ü V W X Y Z`  
`a ä b c ç d e f g ğ h i ĩ j k l m n ň o ö p q r s ş t u ü v w x y z`

### Main (Ą ą = Ä ä; Ǫ ǫ = Ö ö; Ų ų = Ü ü; Ŋ ŋ = Ñ ñ)
`A Ą B C Ç D E F G Ğ H I Ī J K L M N Ŋ O Ǫ P Q R S Ş T U Ų V W X Y Z`  
`a ą b c ç d e f g ğ h i ī j k l m n ŋ o ǫ p q r s ş t u ų v w x y z`

## Cyrillic

### Main
`А Ә Б Җ Ч Д Е Ф Г Ғ Һ И Ы Ж К Л М Н Ң О Ө П Қ Р С Ш Т У Ү В Ў Х Й З`  
`а ә б җ ч д е ф г ғ һ и ы ж к л м н ң о ө п қ р с ш т у ү в ў х й з`

### Additional
`Ҫ Ҙ Ц`  
`ҫ ҙ ц`

#### Additional Azerbaijani (Q q - Ҝ ҝ; C c - Ҹ ҹ)
`Ҝ Ҹ`  
`ҝ ҹ`
