---
layout: default
title: Seja Bem Vindo, a Next Job!
---
<table align="center" class="list_block block-6" width="100%" border="0" cellpadding="10" cellspacing="0" role="presentation" style="mso-table-lspace: 0pt; mso-table-rspace: 0pt; word-break: break-word; color: #292f33; direction: ltr; font-family: 'Roboto', Tahoma, Verdana, Segoe, sans-serif; font-size: 14px; font-weight: 400; letter-spacing: 0px; line-height: 1.2; text-align: left; mso-line-height-alt: 17px;">
 <tr>
  <td class="pad">
   <div style="margin-left:-20px">
    <ul style="margin-top: 0; margin-bottom: 0; list-style-type: revert;">
     {% for post in site.posts %}<li style="Margin: 0 0 0 0;"><a href="{{ post.url }}">{{ post.title }}</a></li>{% endfor %}
     <!--<li style="Margin: 0 0 0 0;">Esta é uma lista não ordenada</li>-->
    </ul>
   </div>
  </td>
 </tr>
</table>
