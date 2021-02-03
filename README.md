# MedicalData
The peculiarity of this approach is based on the need to automate and informatize multiparameter biomedical indicators, the number of records which reaches millions in the medical information system qMS (developer – joint stock company “SPARM”, Saint-Petersburg, Russia) stored on servers in [Almazov National Medical Research Centre, St. Petersburg, Russia] (http://www.almazovcentre.ru/?lang=en). In addition, the parameter sets themselves can consist of several dozens of indicators. Thus, the task is to give the doctor an integral convolution of indicators of the medical system, adequately describing and understandable to medical personnel. It also presents one of the ways to process Big Data in the medical field. Clinical materials were collected by doctors Kurapeev D. I. and Kabanov V. O.

The dynamics of acid-base state (ABS) of circulating blood in the artery and in the cavernous sinus (CS) was studied in 3 groups consisting of 391 patients with cardiac pathology in the postoperative period in the operating room and in the cardio-resuscitation Department at 6 points. The ABS system consisting of 21 biochemical parameters was considered. The parameters are given in the table. The results of dynamics simulation in CS are discussed in article. In the present study, the task was to build similar models for ABS dynamics in the artery and compare it with ABS dynamics in CS by the following methods.
# Parameters of ABS
<table class=MsoNormalTable border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none'>
 <tr>
  <td width=86 valign=top style='width:64.65pt;border:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default align=center style='text-align:center'><b><span lang=EN-US
  style='font-size:10.0pt;font-family:"Times New Roman",serif;color:windowtext'>Parameter
  name</span></b></p>
  </td>
  <td width=225 valign=top style='width:168.95pt;border:solid windowtext 1.0pt;
  border-left:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default align=center style='text-align:center'><b><span lang=EN-US
  style='font-size:10.0pt;font-family:"Times New Roman",serif;color:windowtext'>Description
  of the parameter</span></b></p>
  </td>
  <td width=85 valign=top style='width:63.85pt;border:solid windowtext 1.0pt;
  border-left:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default align=center style='text-align:center'><b><span lang=EN-US
  style='font-size:10.0pt;font-family:"Times New Roman",serif;color:windowtext'>Parameter
  name</span></b></p>
  </td>
  <td width=226 valign=top style='width:169.8pt;border:solid windowtext 1.0pt;
  border-left:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default align=center style='text-align:center'><b><span lang=EN-US
  style='font-size:10.0pt;font-family:"Times New Roman",serif;color:windowtext'>Description
  of the parameter</span></b></p>
  </td>
 </tr>
 <tr>
  <td width=86 valign=top style='width:64.65pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=RU style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>рН</span></p>
  </td>
  <td width=225 valign=top style='width:168.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default><span lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Acidity</span></p>
  </td>
  <td width=85 valign=top style='width:63.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Ca++</span></p>
  </td>
  <td width=226 valign=top style='width:169.8pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Calcium ion concentration</span></p>
  </td>
 </tr>
 <tr>
  <td width=86 valign=top style='width:64.65pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=RU style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>рО2</span></p>
  </td>
  <td width=225 valign=top style='width:168.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Oxygen partial pressure</span></p>
  </td>
  <td width=85 valign=top style='width:63.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Cl-</span></p>
  </td>
  <td width=226 valign=top style='width:169.8pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Chlorine Ion concentration</span></p>
  </td>
 </tr>
 <tr>
  <td width=86 valign=top style='width:64.65pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=RU style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>рСО2</span></p>
  </td>
  <td width=225 valign=top style='width:168.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Carbon dioxide partial pressure</span></p>
  </td>
  <td width=85 valign=top style='width:63.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Glu</span></p>
  </td>
  <td width=226 valign=top style='width:169.8pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Glucose concentration</span></p>
  </td>
 </tr>
 <tr>
  <td width=86 valign=top style='width:64.65pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=RU style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>АВЕ</span></p>
  </td>
  <td width=225 valign=top style='width:168.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Excess base</span></p>
  </td>
  <td width=85 valign=top style='width:63.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Lac</span></p>
  </td>
  <td width=226 valign=top style='width:169.8pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Lactate content</span></p>
  </td>
 </tr>
 <tr>
  <td width=86 valign=top style='width:64.65pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>SBE</span></p>
  </td>
  <td width=225 valign=top style='width:168.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Lack of reason</span></p>
  </td>
  <td width=85 valign=top style='width:63.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>p50</span></p>
  </td>
  <td width=226 valign=top style='width:169.8pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Hemoglobin affinity for oxygen</span></p>
  </td>
 </tr>
 <tr>
  <td width=86 valign=top style='width:64.65pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>cHCO</span><span lang=RU style='font-size:10.0pt;
  font-family:"Times New Roman",serif;color:windowtext'>3</span></p>
  </td>
  <td width=225 valign=top style='width:168.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Plasma bicarbonate</span></p>
  </td>
  <td width=85 valign=top style='width:63.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>mOsm</span></p>
  </td>
  <td width=226 valign=top style='width:169.8pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Blood osmolarity</span></p>
  </td>
 </tr>
 <tr>
  <td width=86 valign=top style='width:64.65pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>cHCO3-st</span></p>
  </td>
  <td width=225 valign=top style='width:168.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Bicarbonate (alkali)</span></p>
  </td>
  <td width=85 valign=top style='width:63.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>pH(T)</span></p>
  </td>
  <td width=226 valign=top style='width:169.8pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Acidity corrected for temperature</span></p>
  </td>
 </tr>
 <tr>
  <td width=86 valign=top style='width:64.65pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>sO2</span></p>
  </td>
  <td width=225 valign=top style='width:168.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Oxygen boost</span></p>
  </td>
  <td width=85 valign=top style='width:63.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>pO2(T)</span></p>
  </td>
  <td width=226 valign=top style='width:169.8pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Partial oxygen pressure adjusted for temperature</span></p>
  </td>
 </tr>
 <tr style='height:25.5pt'>
  <td width=86 valign=top style='width:64.65pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt;height:25.5pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>ctHb</span></p>
  </td>
  <td width=225 valign=top style='width:168.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:25.5pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Reference hemoglobin level</span></p>
  </td>
  <td width=85 valign=top style='width:63.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:25.5pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>pCO2(T)</span></p>
  </td>
  <td width=226 valign=top style='width:169.8pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:25.5pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Carbon dioxide partial pressure adjusted for temperature</span></p>
  </td>
 </tr>
 <tr>
  <td width=86 valign=top style='width:64.65pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>K+</span></p>
  </td>
  <td width=225 valign=top style='width:168.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Potassium ion concentration</span></p>
  </td>
  <td width=85 valign=top style='width:63.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Na+</span></p>
  </td>
  <td width=226 valign=top style='width:169.8pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Sodium ion concentration</span></p>
  </td>
 </tr>
 <tr>
  <td width=86 valign=top style='width:64.65pt;border:solid windowtext 1.0pt;
  border-top:none;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Htc</span></p>
  </td>
  <td width=225 valign=top style='width:168.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>Hematocrit</span></p>
  </td>
  <td width=85 valign=top style='width:63.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>&nbsp;</span></p>
  </td>
  <td width=226 valign=top style='width:169.8pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=Default style='text-align:justify;text-justify:inter-ideograph'><span
  lang=EN-US style='font-size:10.0pt;font-family:"Times New Roman",serif;
  color:windowtext'>&nbsp;</span></p>
  </td>
 </tr>
</table>	
