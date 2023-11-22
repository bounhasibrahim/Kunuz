<h1>Kunuz-IR</h1>

<div class=WordSection1>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-family:"Times New Roman",serif'>This resource is a bilingual Information
Retrieval (IR) collection built according to <a href="https://trec.nist.gov/"><span
style='font-size:9.0pt;line-height:115%'>TREC</span></a> guidelines and data
formats. Data was extracted from an
XMLized version of Sahih Albukhari, the most authentic hadith book. </span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-family:"Times New Roman",serif'>The dataset is structured as
follows:</span></p>

<p class=MsoListParagraphCxSpFirst style='text-align:justify;text-indent:-18.0pt'><span
lang=EN-US style='font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span dir=LTR></span><span lang=EN-US style='font-family:"Times New Roman",serif'>At
the macro-logical level, the collection t is structured through sections in a
hierarchical manner (see&nbsp;<b>Structure.xml</b>). From this structure, we
extracted a list of domains (<b>Domains.txt</b>)&nbsp; and an index linking
domains to hadiths (<b>Domain-Index.txt</b>).</span></p>

<p class=MsoListParagraphCxSpLast style='text-align:justify;text-indent:-18.0pt'><span
style='font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span dir=LTR></span><span lang=EN-US style='font-family:"Times New Roman",serif'>At
the micro-logical level, the hadiths are fully tagged; mainly narrator names,
Quran verses and the real content of each hadith (metn) are recognized (see
&quot;<b>Micro-Documents</b>&quot;&nbsp;folder). This resource may be used for
Named Entity Recognition (NER) applications and in general for information
extraction from Arabic documents. </span><span style='font-family:"Times New Roman",serif'>The
main tags are summarized as follows:</span></p>

<div align=center>

<table class=MsoTable15Grid4 border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none'>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid black 1.0pt;
  border-right:none;background:black;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span style='font-family:"Times New Roman",serif;color:white'>Tag</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border:solid black 1.0pt;
  border-left:none;background:black;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span style='font-family:"Times New Roman",serif;color:white'>Significance</span></b></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span style='font-family:"Times New Roman",serif;color:black'>Metn
  or M</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span style='font-family:"Times New Roman",serif;color:black'>The
  real content of the hadith (</span><span lang=AR-SA dir=RTL style='font-family:
  "Times New Roman",serif;color:black'>&#1575;&#1604;&#1605;&#1578;&#1606;</span><span
  dir=LTR></span><span style='font-family:"Times New Roman",serif;color:black'><span
  dir=LTR></span>)</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span style='font-family:"Times New Roman",serif'>Sanad</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span style='font-family:"Times New Roman",serif'>Chain of narrators
  (</span><span lang=AR-SA dir=RTL style='font-family:"Times New Roman",serif'>&#1575;&#1604;&#1587;&#1606;&#1583;</span><span
  dir=LTR></span><span style='font-family:"Times New Roman",serif'><span
  dir=LTR></span>)</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span style='font-family:"Times New Roman",serif;color:black'>S</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span style='font-family:"Times New Roman",serif;color:black'>Section</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span style='font-family:"Times New Roman",serif'>TI</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span style='font-family:"Times New Roman",serif'>Title of a section</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>Q</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>Quranic verse</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif'>C</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif'>Poesy</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>R</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>Narrator</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif'>bkh</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif'>The name
  of the author (i.e. Al-Bukhari)</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>qwl</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>Indicates the hadith contains a speech of the prophet PBUH.</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif'>pbuh</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif'>The name
  of the prophet PBUH.</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>proph</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>The names of the prophets.</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif'>mlk</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif'>The
  names of anges.</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>trb</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>Names of islamic  doctrines</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif'>rel</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif'>Names of
  religions and holy books</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>plc</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>Names of places</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif'>wem</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif'>Names of
  women</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>cmtbkh</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>Comments of the author (i.e. Al-Bukhari)</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif'>cmt</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif'>Comments
  (e.g. definitions)</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>fnarmetn</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>First narrator and metn</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif'>C</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif'>Poesy</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>poepart</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>Part of poesy</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif'>qpart</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif'>Names of
  quranic surats or parts</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>cmtcre</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  background:#CCCCCC;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif;
  color:black'>Credibility comment</span></p>
  </td>
 </tr>
 <tr>
  <td width=140 valign=top style='width:104.65pt;border:solid #666666 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><b><span lang=EN-US style='font-family:"Times New Roman",serif'>qvpart</span></b></p>
  </td>
  <td width=416 valign=top style='width:11.0cm;border-top:none;border-left:
  none;border-bottom:solid #666666 1.0pt;border-right:solid #666666 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal style='margin-bottom:0cm;text-align:justify;line-height:
  normal'><span lang=EN-US style='font-family:"Times New Roman",serif'>A part
  of a quranic verse</span></p>
  </td>
 </tr>
</table>

</div>

<p class=MsoListParagraphCxSpFirst style='text-align:justify;text-indent:-18.0pt'><span
lang=EN-US style='font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span dir=LTR></span><span lang=EN-US style='font-family:"Times New Roman",serif'>The
attribute &quot;l&quot; of each section tag indicates its level e.g. (S
l=&quot;1&quot;) stands for a section of level one; (S l=&quot;2&quot;)
represents a sub-section.</span></p>

<p class=MsoListParagraphCxSpMiddle style='text-align:justify;text-indent:-18.0pt'><span
lang=EN-US style='font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span dir=LTR></span><span lang=EN-US style='font-family:"Times New Roman",serif'>We
also provide full documents containing hadiths and their explanations in the
TREC XML format (<b>Full-Documents-Trec</b>&nbsp;folder)</span></p>

<p class=MsoListParagraphCxSpLast style='text-align:justify;text-indent:-18.0pt'><span
lang=EN-US style='font-family:Symbol'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span><span dir=LTR></span><span lang=EN-US style='font-family:"Times New Roman",serif'>The
collection is designed for assessing Information Retrieval (IR) systems. We
collected a set of standard topics (<b>Queries.xml</b>) and relevance judgments
according to standard topic development and sampling procedures of RI campaigns
(see&nbsp;<b>Qrels.txt</b>).</span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-family:"Times New Roman",serif'>The resource is available for free
usage for the research community. It is distributed under a&nbsp;</span><span
style='font-family:"Times New Roman",serif'><a
href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><span lang=EN-US
style='color:#027AC6'>Creative Commons Attribution-NonCommercial-NoDerivatives
4.0 International License</span></a></span><span lang=EN-US style='font-family:
"Times New Roman",serif'>. When using it, you are encouraged to cite:</span></p>

<p class=MsoNormal style='text-align:justify'><u><span lang=EN-US
style='font-family:"Times New Roman",serif;color:#027AC6'>I. Bounhas</span></u><span
lang=EN-US style='font-family:"Times New Roman",serif'>,&nbsp;<u><span
style='color:#027AC6'>“</span></u><b><span style='color:#027AC6'>On the Usage
of a Classical Arabic Corpus as a Language Resource: Related Research and Key
Challenges</span></b><u><span style='color:#027AC6'>”</span></u>,&nbsp;<i>ACM
Transactions on Asian and Low-Resource Language Information Processing</i>,
vol. 18, no. 3, p. Article N°23, 2019.</span></p>

<p class=MsoNormal style='text-align:justify'><u><span lang=EN-US
style='font-size:10.5pt;line-height:115%;font-family:"Times New Roman",serif;
color:#027AC6'>I. Bounhas</span></u><span lang=EN-US style='font-size:10.5pt;
line-height:115%;font-family:"Times New Roman",serif;color:black'>&nbsp;and&nbsp;</span><u><span
lang=EN-US style='font-size:10.5pt;line-height:115%;font-family:"Times New Roman",serif;
color:#027AC6'>Ben Guirat, S.</span></u><span lang=EN-US style='font-size:10.5pt;
line-height:115%;font-family:"Times New Roman",serif;color:black'>,&nbsp;</span><u><span
lang=EN-US style='font-size:10.5pt;line-height:115%;font-family:"Times New Roman",serif;
color:#027AC6'>“</span></u><b><span lang=EN-US style='font-size:10.5pt;
line-height:115%;font-family:"Times New Roman",serif;color:#027AC6'>KUNUZ: a
Multi-purpose Reusable Test Collection for Classical Arabic Document
Engineering</span></b><u><span lang=EN-US style='font-size:10.5pt;line-height:
115%;font-family:"Times New Roman",serif;color:#027AC6'>”</span></u><span
lang=EN-US style='font-size:10.5pt;line-height:115%;font-family:"Times New Roman",serif;
color:black'>, in&nbsp;</span><i><span lang=EN-US style='font-family:"Times New Roman",serif'>Proceedings
of the 16th CS/IEEE International Conference on Computer Systems and
Applications (AICSSA), Abu Dhabi, UAE, November 03-07, 2019</span></i><span
lang=EN-US style='font-size:10.5pt;line-height:115%;font-family:"Times New Roman",serif;
color:black'>, Abu Dhabi, UAE, 2019.</span></p>

<p class=MsoNormal style='text-align:justify'><span lang=EN-US
style='font-family:"Times New Roman",serif'>&nbsp;</span></p>

</div>
