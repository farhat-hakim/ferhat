<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='false' b:defaultwidgetversion='2' b:layoutsVersion='3' b:responsive='true' b:templateVersion='1.3.0' expr:class='data:blog.languageDirection' expr:dir='data:blog.languageDirection' expr:lang='data:blog.localeUnderscoreDelimited' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
<b:include name='dark-mode'/>
<head>
<b:include name='theme-head'/>
<b:if cond='!data:view.isLayoutMode'>
<b:skin version='1.3.0'><![CDATA[/*
-----------------------------------------------
Blogger Template Style
Name:         farhat-dz
Version:      1.3.0 - Premium
Author:       Pro  Templates
Author Url:   https://stepnewsreviews.blogspot.com/?m=1
-----------------------------------------------*/

/*-- Customize Options (Start) --
<Variable name="keycolor" description="Main Color" type="color" default="#f12f3f" value="#f12f3f"/>
<Group description="Theme Options" selector="body">
    <Variable name="darkmode" description="Native Dark Mode" type="length" default="0px" min="0px" max="1px" value="0px"/>
    <Variable name="userdarkmode" description="User Dark Mode" type="length" default="1px" min="0px" max="1px" value="1px"/>
    <Variable name="boxed" description="Boxed Mode" type="length" default="0px" min="0px" max="1px" value="0px"/>
    <Variable name="sidebar" description="Left Sidebar" type="length" default="0px" min="0px" max="1px" value="0px"/>
    <Variable name="fixedmenu" description="Fixed Menu" type="length" default="1px" min="0px" max="1px" value="1px"/>
    <Variable name="fixedsidebar" description="Fixed Sidebar" type="length" default="1px" min="0px" max="1px" value="1px"/>
</Group>
<Group description="Widths" selector="body">
    <Variable name="row.width" description="Container Width" type="length" default="1073px" min="970px" max="1094px" value="1073px"/>
    <Variable name="sidebar.width" description="Sidebar Width" type="length" default="320px" min="250px" max="336px" value="320px"/>
</Group>
<Group description="Fonts" selector="body">
    <Variable name="main.font" description="Main Font" type="font" family="Montserrat" default="normal 400 14px $(family)" value="normal 400 14px $(family)"/>
    <Variable name="menu.font" description="Menu Font" type="font" family="Montserrat" default="normal 400 14px $(family)" value="normal 400 14px $(family)"/>
    <Variable name="title.font" description="Title Font" type="font" family="Montserrat" default="normal 400 14px $(family)" value="normal 400 14px $(family)"/>
    <Variable name="text.font" description="Text Font" type="font" family="Montserrat" default="normal 400 14px $(family)" value="normal 400 14px $(family)"/>
</Group>
<Group description="Background" selector="body">
	<Variable name="background.color" description="Body Background (Boxed)" type="color" default="#e5e6e7"  value="#e5e6e7"/>
    <Variable name="outer.bg" description="Outer Background" type="color" default="#f4f4f4"  value="#f4f4f4"/>
	<Variable name="widget.bg" description="Widget Background" type="color" default="#ffffff" value="#ffffff"/>
    <Variable name="border.color" description="Border Color" type="color" default="#f5f5f5"  value="#f5f5f5"/>
</Group>
<Group description="Colors" selector="body">
    <Variable name="main.color" description="Main Color" type="color" default="#f12f3f" value="#f12f3f"/>
    <Variable name="title.color" description="Title Color" type="color" default="#222222" value="#222222"/>
    <Variable name="title.hover.color" description="Title Hover Color" type="color" default="$(main.color)" value="#f12f3f"/>
    <Variable name="text.color" description="Text Color" type="color" default="#626262"  value="#626262"/>
    <Variable name="meta.color" description="Meta Color" type="color" default="#97979d" value="#97979d"/>
    <Variable name="meta.link" description="Meta Link Color" type="color" default="$(main.color)" value="#f12f3f"/>
</Group>
<Group description="Top Ads" selector="#top-ads-wrap">
    <Variable name="topad.onpost" description="Show on Post Page" type="length" default="1px" min="0px" max="1px" value="1px"/>
	<Variable name="topad.bg" description="Background" type="color" default="$(outer.bg)" value="#f4f4f4"/>
    <Variable name="topad.border" description="Show Border" type="length" default="0px" min="0px" max="1px" value="0px"/>
	<Variable name="topad.border.color" description="Border Color" type="color" default="$(border.color)" value="#f5f5f5"/>
</Group>
<Group description="Header" selector="#header-wrapper">
    <Variable name="header.height" description="Height" type="length" default="62px" min="50px" max="70px" value="62px"/>
    <Variable name="header.left" description="Background (Left)" type="color" default="#ffffff" value="#ffffff"/>
    <Variable name="header.center" description="Background (Center)" type="color" default="#ffffff" value="#ffffff"/>
    <Variable name="header.right" description="Background (Right)" type="color" default="#ffffff" value="#ffffff"/>
    <Variable name="header.color" description="Color" type="color" default="$(title.color)" value="#222222"/>
    <Variable name="header.hover.color" description="Hover Color" type="color" default="$(main.color)" value="#f12f3f"/>
</Group>
<Group description="Sub Menu" selector="#header-wrapper">
    <Variable name="submenu.bg" description="Background" type="color" default="#ffffff" value="#ffffff"/>
    <Variable name="submenu.color" description="Color" type="color" default="$(title.color)" value="#222222"/>
    <Variable name="submenu.hover.color" description="Hover Color" type="color" default="$(main.color)" value="#f12f3f"/>
</Group>
<Group description="Mega Menu" selector="#header-wrapper">
    <Variable name="mega.bg" description="Background" type="color" default="$(submenu.bg)" value="#ffffff"/>
    <Variable name="mega.color" description="Color" type="color" default="$(submenu.color)" value="#222222"/>
    <Variable name="mega.hover.color" description="Hover Color" type="color" default="$(main.color)" value="#f12f3f"/>
    <Variable name="mega.meta.color" description="Meta Color" type="color" default="$(meta.color)" value="#97979d"/>
</Group>
<Group description="Mobile Menu" selector="body">
    <Variable name="mobilemenu.bg" description="Background" type="color" default="#ffffff" value="#ffffff"/>
    <Variable name="mobilemenu.color" description="Color" type="color" default="$(title.color)" value="#222222"/>
    <Variable name="mobilemenu.hover.color" description="Hover Color" type="color" default="$(main.color)" value="#f12f3f"/>
</Group>
<Group description="Ticker" selector="#header-wrapper">
    <Variable name="ticker.onpost" description="Show on Post Page" type="length" default="1px" min="0px" max="1px" value="1px"/>
    <Variable name="ticker.bg" description="Background" type="color" default="#ffffff" value="#ffffff"/>
    <Variable name="ticker.icon" description="Icon Color" type="color" default="$(main.color)" value="#f12f3f"/>
    <Variable name="ticker.title" description="Headline Color" type="color" default="$(title.color)" value="#222222"/>
    <Variable name="ticker.color" description="Title Color" type="color" default="$(text.color)" value="#626262"/>
    <Variable name="ticker.hover.color" description="Hover Color" type="color" default="$(main.color)" value="#f12f3f"/>
    <Variable name="ticker.border" description="Show Border" type="length" default="1px" min="0px" max="1px" value="1px"/>
    <Variable name="ticker.border.color" description="Border Color" type="color" default="$(border.color)" value="#f5f5f5"/>
</Group>
<Group description="Blog Posts" selector="body">
    <Variable name="gridstyle" description="Grid Style" type="length" default="0px" min="0px" max="1px" value="0px"/>
    <Variable name="summary" description="Show Summary" type="length" default="1px" min="0px" max="1px" value="1px"/>
</Group>
<Group description="Thumb Tags" selector="body">
    <Variable name="thumbtag" description="Show Thumb Tag" type="length" default="1px" min="0px" max="1px" value="1px"/>
    <Variable name="thumbtag.left" description="Background (Left)" type="color" default="#f8491b" value="#f8491b"/>
    <Variable name="thumbtag.center" description="Background (Center)" type="color" default="#f12f3f" value="#f12f3f"/>
    <Variable name="thumbtag.right" description="Background (Right)" type="color" default="#dc1860" value="#dc1860"/>
    <Variable name="thumbtag.color" description="Color" type="color" default="#ffffff" value="#ffffff"/>
</Group>
<Group description="Entry Tags" selector="body">
    <Variable name="entrytag" description="Show Entry Tag" type="length" default="1px" min="0px" max="1px" value="1px"/>
    <Variable name="entrytag.color" description="Color" type="color" default="$(main.color)" value="#f12f3f"/>
</Group>
<Group description="Post Page" selector="body">
    <Variable name="breadcrumb" description="Breadcrumbs" type="length" default="1px" min="0px" max="1px" value="1px"/>
    <Variable name="itempost.title.size" description="Title Font Size" type="length" default="33px" min="20px" max="50px" value="33px"/>
    <Variable name="itempost.content.size" description="Text Font Size" type="length" default="15px" min="12px" max="20px" value="15px"/>
    <Variable name="postnav" description="Navigation" type="length" default="1px" min="0px" max="1px" value="1px"/>
</Group>
<Group description="Footer Ads" selector="#footer-ads-wrap">
    <Variable name="footerad.onpost" description="Show on Post Page" type="length" default="1px" min="0px" max="1px" value="1px"/>
	<Variable name="footerad.bg" description="Background" type="color" default="$(widget.bg)" value="#ffffff"/>
    <Variable name="footerad.border" description="Show Border" type="length" default="0px" min="0px" max="1px" value="0px"/>
	<Variable name="footerad.border.color" description="Border Color" type="color" default="$(border.color)" value="#f5f5f5"/>
</Group>
<Group description="Footer" selector="#footer-wrapper">
    <Variable name="footer.bg" description="Background" type="color" default="#16161a" value="#16161a"/>
    <Variable name="footer.color" description="Color" type="color" default="#ffffff" value="#ffffff"/>
    <Variable name="footer.text.color" description="Text Color" type="color" default="#AAAAAA" value="#AAAAAA"/>
</Group>
<Group description="Footer Bar" selector="div.footer-bar">
    <Variable name="footerbar.bg" description="Background" type="color" default="#09090a" value="#09090a"/>
    <Variable name="footerbar.color" description="Color" type="color" default="#ffffff" value="#ffffff"/>
    <Variable name="footerbar.hover.color" description="Hover Color" type="color" default="$(main.color)" value="#f12f3f"/>
    <Variable name="footerbar.border" description="Show Border" type="length" default="0px" min="0px" max="1px" value="0px"/>
    <Variable name="footerbar.border.color" description="Border Color" type="color" default="#2b2b2f" value="#2b2b2f"/>
</Group>
<Group description="Cookie Consent" selector="#buzzspot-pro-cookie-consent">
    <Variable name="cookie.bg" description="Background" type="color" default="#ffffff" value="#ffffff"/>
    <Variable name="cookie.color" description="Text Color" type="color" default="$(text.color)" value="#626262"/>
</Group>
<Group description="Buttons" selector="body">
    <Variable name="btn.left" description="Background (Left)" type="color" default="#f8491b" value="#f8491b"/>
    <Variable name="btn.center" description="Background (Center)" type="color" default="#f12f3f" value="#f12f3f"/>
    <Variable name="btn.right" description="Background (Right)" type="color" default="#dc1860" value="#dc1860"/>
    <Variable name="btn.color" description="Color" type="color" default="#ffffff" value="#ffffff"/>
</Group>
<Group description="Dark Mode" selector="body">
    <Variable name="dark.bg" description="Body Background" type="color" default="#27272b" value="#27272b"/>
    <Variable name="dark1.bg" description="Background 1" type="color" default="#16161a" value="#16161a"/>
    <Variable name="dark2.bg" description="Background 2" type="color" default="#202024" value="#202024"/>
    <Variable name="dark3.bg" description="Background 3" type="color" default="#252529" value="#252529"/>
    <Variable name="dark.main.color" description="Main Color" type="color" default="$(main.color)" value="#f12f3f"/>
    <Variable name="dark.title" description="Title Color" type="color" default="#f8f8fb" value="#f8f8fb"/>
    <Variable name="dark.text" description="Text Color" type="color" default="#c5c5c8" value="#c5c5c8"/>
    <Variable name="dark.meta" description="Meta Color" type="color" default="#aaaaaa" value="#aaaaaa"/>
    <Variable name="dark.meta.link" description="Meta Link Color" type="color" default="$(dark.main.color)" value="#f12f3f"/>
    <Variable name="dark.border" description="Border Color" type="color" default="#2b2b2f"  value="#2b2b2f"/>
</Group>
<Group description="Fix Blur (Fonts)" selector="body">
    <!-- Site Font -->
    <Variable name="mainfont.italic" description="Main Font Italic" type="font" default="italic 400 14px $(main.font.family)" value="italic 400 14px $(family)"/>
    <Variable name="mainfont.medium" description="Main Font Medium" type="font" default="normal 500 14px $(main.font.family)" value="normal 500 14px $(family)"/>
    <Variable name="mainfont.medium.italic" description="Main Font Medium Italic" type="font" default="italic 500 14px $(main.font.family)" value="italic 500 14px $(family)"/>
    <Variable name="mainfont.semibold" description="Main Font Semi Bold" type="font" default="normal 600 14px $(main.font.family)" value="normal 600 14px $(family)"/>
    <Variable name="mainfont.semibold.italic" description="Main Font Semi Bold Italic" type="font" default="italic 600 14px $(main.font.family)" value="italic 600 14px $(family)"/>
    <Variable name="mainfont.bold" description="Main Font Bold" type="font" default="normal 700 14px $(main.font.family)" value="normal 700 14px $(family)"/>
    <Variable name="mainfont.bold.italic" description="Main Font Bold Italic" type="font" default="italic 700 14px $(main.font.family)" value="italic 700 14px $(family)"/>
    <!-- Menu Font -->
    <Variable name="menufont.bold" description="Menu Font Bold" type="font" default="normal 700 14px $(menu.font.family)" value="normal 700 14px $(family)"/>
    <!-- Title Font -->
    <Variable name="titlefont.bold" description="Title Font Bold" type="font" default="normal 700 14px $(title.font.family)" value="normal 700 14px $(family)"/>
    <Variable name="titlefont.bold.italic" description="Title Font Bold Italic" type="font" default="italic 700 14px $(title.font.family)" value="italic 700 14px $(family)"/>
    <!-- Text Font -->
    <Variable name="textfont.italic" description="Text Font Italic" type="font" default="italic 400 14px $(text.font.family)" value="italic 400 14px $(family)"/>
    <Variable name="textfont.bold" description="Text Font Bold" type="font" default="normal 700 14px $(text.font.family)" value="normal 700 14px $(family)"/>
    <Variable name="textfont.bold.italic" description="Text Font Bold Italic" type="font" default="italic 700 14px $(text.font.family)" value="italic 700 14px $(family)"/>
</Group>
<Variable name="body.background" description="Background" type="background" color="$(background.color)" default="$(color) none repeat fixed top left" value="$(color) none repeat fixed top left"/>
<Variable name="body.background.color" description="Comments Background" hideEditor="true" type="color" default="transparent"  value="transparent"/>
<Variable name="body.title.color" description="Comments Color" hideEditor="true" type="color" default="$(title.color)" value="#222222"/>
<Variable name="body.text.color" description="Comments Text Color" hideEditor="true" type="color" default="$(text.color)"  value="#626262"/>
<Variable name="body.link.color" description="Comments Link Color" hideEditor="true" type="color" default="$(main.color)"  value="#f12f3f"/>
<Variable name="body.text.font" description="Comments Font 1" hideEditor="true" type="font" default="normal 400 14px montserrat, Arial, sans-serif !important"  value="normal 400 14px montserrat, Arial, sans-serif !important"/>
<Variable name="body.action.font.large" description="Comments Font 2" hideEditor="true" type="font" default="normal 700 14px montserrat, Arial, sans-serif !important"  value="normal 700 14px montserrat, Arial, sans-serif !important"/>
-- Customize Options (End) --*/

/*-- Google Fonts --*/
@font-face{font-family:'Montserrat';font-style:italic;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUQjIg1_i6t8kCHKm459WxRxC7mw9c.woff2) format("woff2");unicode-range:U+0460-052F,U+1C80-1C88,U+20B4,U+2DE0-2DFF,U+A640-A69F,U+FE2E-FE2F}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUQjIg1_i6t8kCHKm459WxRzS7mw9c.woff2) format("woff2");unicode-range:U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUQjIg1_i6t8kCHKm459WxRxi7mw9c.woff2) format("woff2");unicode-range:U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+1EA0-1EF9,U+20AB}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUQjIg1_i6t8kCHKm459WxRxy7mw9c.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUQjIg1_i6t8kCHKm459WxRyS7m.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUPjIg1_i6t8kCHKm459WxZOg3z8fZwnCo.woff2) format("woff2");unicode-range:U+0460-052F,U+1C80-1C88,U+20B4,U+2DE0-2DFF,U+A640-A69F,U+FE2E-FE2F}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUPjIg1_i6t8kCHKm459WxZOg3z-PZwnCo.woff2) format("woff2");unicode-range:U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUPjIg1_i6t8kCHKm459WxZOg3z8_ZwnCo.woff2) format("woff2");unicode-range:U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+1EA0-1EF9,U+20AB}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUPjIg1_i6t8kCHKm459WxZOg3z8vZwnCo.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUPjIg1_i6t8kCHKm459WxZOg3z_PZw.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUPjIg1_i6t8kCHKm459WxZFgrz8fZwnCo.woff2) format("woff2");unicode-range:U+0460-052F,U+1C80-1C88,U+20B4,U+2DE0-2DFF,U+A640-A69F,U+FE2E-FE2F}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUPjIg1_i6t8kCHKm459WxZFgrz-PZwnCo.woff2) format("woff2");unicode-range:U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUPjIg1_i6t8kCHKm459WxZFgrz8_ZwnCo.woff2) format("woff2");unicode-range:U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+1EA0-1EF9,U+20AB}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUPjIg1_i6t8kCHKm459WxZFgrz8vZwnCo.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUPjIg1_i6t8kCHKm459WxZFgrz_PZw.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUPjIg1_i6t8kCHKm459WxZcgvz8fZwnCo.woff2) format("woff2");unicode-range:U+0460-052F,U+1C80-1C88,U+20B4,U+2DE0-2DFF,U+A640-A69F,U+FE2E-FE2F}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUPjIg1_i6t8kCHKm459WxZcgvz-PZwnCo.woff2) format("woff2");unicode-range:U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUPjIg1_i6t8kCHKm459WxZcgvz8_ZwnCo.woff2) format("woff2");unicode-range:U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+1EA0-1EF9,U+20AB}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUPjIg1_i6t8kCHKm459WxZcgvz8vZwnCo.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Montserrat';font-style:italic;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUPjIg1_i6t8kCHKm459WxZcgvz_PZw.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUSjIg1_i6t8kCHKm459WRhyzbi.woff2) format("woff2");unicode-range:U+0460-052F,U+1C80-1C88,U+20B4,U+2DE0-2DFF,U+A640-A69F,U+FE2E-FE2F}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUSjIg1_i6t8kCHKm459W1hyzbi.woff2) format("woff2");unicode-range:U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUSjIg1_i6t8kCHKm459WZhyzbi.woff2) format("woff2");unicode-range:U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+1EA0-1EF9,U+20AB}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUSjIg1_i6t8kCHKm459Wdhyzbi.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:400;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTUSjIg1_i6t8kCHKm459Wlhyw.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTURjIg1_i6t8kCHKm45_ZpC3gTD_u50.woff2) format("woff2");unicode-range:U+0460-052F,U+1C80-1C88,U+20B4,U+2DE0-2DFF,U+A640-A69F,U+FE2E-FE2F}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTURjIg1_i6t8kCHKm45_ZpC3g3D_u50.woff2) format("woff2");unicode-range:U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTURjIg1_i6t8kCHKm45_ZpC3gbD_u50.woff2) format("woff2");unicode-range:U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+1EA0-1EF9,U+20AB}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTURjIg1_i6t8kCHKm45_ZpC3gfD_u50.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:500;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTURjIg1_i6t8kCHKm45_ZpC3gnD_g.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTURjIg1_i6t8kCHKm45_bZF3gTD_u50.woff2) format("woff2");unicode-range:U+0460-052F,U+1C80-1C88,U+20B4,U+2DE0-2DFF,U+A640-A69F,U+FE2E-FE2F}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTURjIg1_i6t8kCHKm45_bZF3g3D_u50.woff2) format("woff2");unicode-range:U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTURjIg1_i6t8kCHKm45_bZF3gbD_u50.woff2) format("woff2");unicode-range:U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+1EA0-1EF9,U+20AB}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTURjIg1_i6t8kCHKm45_bZF3gfD_u50.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:600;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTURjIg1_i6t8kCHKm45_bZF3gnD_g.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTURjIg1_i6t8kCHKm45_dJE3gTD_u50.woff2) format("woff2");unicode-range:U+0460-052F,U+1C80-1C88,U+20B4,U+2DE0-2DFF,U+A640-A69F,U+FE2E-FE2F}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTURjIg1_i6t8kCHKm45_dJE3g3D_u50.woff2) format("woff2");unicode-range:U+0400-045F,U+0490-0491,U+04B0-04B1,U+2116}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTURjIg1_i6t8kCHKm45_dJE3gbD_u50.woff2) format("woff2");unicode-range:U+0102-0103,U+0110-0111,U+0128-0129,U+0168-0169,U+01A0-01A1,U+01AF-01B0,U+1EA0-1EF9,U+20AB}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTURjIg1_i6t8kCHKm45_dJE3gfD_u50.woff2) format("woff2");unicode-range:U+0100-024F,U+0259,U+1E00-1EFF,U+2020,U+20A0-20AB,U+20AD-20CF,U+2113,U+2C60-2C7F,U+A720-A7FF}
@font-face{font-family:'Montserrat';font-style:normal;font-weight:700;font-display:swap;src:url(https://fonts.gstatic.com/s/montserrat/v18/JTURjIg1_i6t8kCHKm45_dJE3gnD_g.woff2) format("woff2");unicode-range:U+0000-00FF,U+0131,U+0152-0153,U+02BB-02BC,U+02C6,U+02DA,U+02DC,U+2000-206F,U+2074,U+20AC,U+2122,U+2191,U+2193,U+2212,U+2215,U+FEFF,U+FFFD}

/*-- Material Icons Font --*/
@font-face{font-family:"Material Icons Round";font-display:swap;font-style:normal;font-weight:400;src:url(https://fonts.gstatic.com/s/materialiconsround/v65/LDItaoyNOAY6Uewc665JcIzCKsKc_M9flwmP.woff2) format("woff2")}.mir{font-family:"Material Icons Round";font-weight:400;font-style:normal;font-size:24px;line-height:1;letter-spacing:normal;text-transform:none;display:inline-block;white-space:nowrap;word-wrap:normal;direction:ltr;-webkit-font-feature-settings:liga;-webkit-font-smoothing:antialiased}@font-face{font-family:"PBT Icons";font-display:block;font-style:normal;font-weight:400;src:url(https://fonts.gstatic.com/s/materialiconsround/v65/LDItaoyNOAY6Uewc665JcIzCKsKc_M9flwmP.woff2) format("woff2")}

/*-- Font Awesome 5 Brands 5.15.4 --*/
@font-face{font-family:"Font Awesome 5 Brands";font-display:swap;font-style:normal;font-weight:400;src:url(https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/webfonts/fa-brands-400.eot);src:url(https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/webfonts/fa-brands-400.eot?#iefix) format("embedded-opentype"),url(https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/webfonts/fa-brands-400.woff2) format("woff2"),url(https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/webfonts/fa-brands-400.woff) format("woff"),url(https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/webfonts/fa-brands-400.ttf) format("truetype"),url(https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/webfonts/fa-brands-400.svg#fontawesome) format("svg")}.fab{font-family:"Font Awesome 5 Brands";font-weight:400}

/*-- CSS Variables --*/
:root{
--body-font:'$(main.font.family)', Arial, sans-serif;
--menu-font:'$(menu.font.family)', Arial, sans-serif;
--title-font:'$(title.font.family)', Arial, sans-serif;
--text-font:'$(text.font.family)', Arial, sans-serif;
--body-bg-color:$(background.color);
--body-bg:$(body.background);
--outer-bg:$(outer.bg);
--main-color:$(main.color);
--title-color:$(title.color);
--title-hover-color:$(title.hover.color);
--text-color:$(text.color);
--meta-color:$(meta.color);
--meta-link-color:$(meta.link);
--thumbtag-bg:linear-gradient(135deg,$(thumbtag.left) 0%,$(thumbtag.center) 50%,$(thumbtag.right) 100%);
--thumbtag-color:$(thumbtag.color);
--entrytag-color:$(entrytag.color);
--topad-bg:$(topad.bg);
--topad-border:$(topad.border.color);
--header-bg:linear-gradient(135deg,$(header.left) 0%,$(header.center) 50%,$(header.right) 100%);
--header-color:$(header.color);
--header-hover-color:$(header.hover.color);
--submenu-bg:$(submenu.bg);
--submenu-color:$(submenu.color);
--submenu-hover-color:$(submenu.hover.color);
--mega-bg:$(mega.bg);
--mega-color:$(mega.color);
--mega-hover-color:$(mega.hover.color);
--mega-meta-color:$(mega.meta.color);
--mobilemenu-bg:$(mobilemenu.bg);
--mobilemenu-color:$(mobilemenu.color);
--mobilemenu-hover-color:$(mobilemenu.hover.color);
--ticker-bg:$(ticker.bg);
--ticker-icon:$(ticker.icon);
--ticker-title:$(ticker.title);
--ticker-color:$(ticker.color);
--ticker-hover-color:$(ticker.hover.color);
--ticker-border:$(ticker.border.color);
--widget-bg:$(widget.bg);
--footerad-bg:$(footerad.bg);
--footerad-border:$(footerad.border.color);
--footer-bg:$(footer.bg);
--footer-color:$(footer.color);
--footer-text-color:$(footer.text.color);
--footerbar-bg:$(footerbar.bg);
--footerbar-color:$(footerbar.color);
--footerbar-hover-color:$(footerbar.hover.color);
--footerbar-border-color:$(footerbar.border.color);
--cookie-bg:$(cookie.bg);
--cookie-color:$(cookie.color);
--button-bg:linear-gradient(135deg,$(btn.left) 0%,$(btn.center) 50%,$(btn.right) 100%);
--button-color:$(btn.color);
--button-border:$(btn.center);
--light-weight:400;
--title-weight:700;
--gray-bg:rgba(155,155,155,0.05);
--border-color:$(border.color);
--radius:5px;
--widget-shadow: 0 1px 2px rgba(0,0,0,0.05);
--avatar-shadow:0px 1px 4px rgba(0,0,0,0.05);
}
html.is-dark{
--body-bg-color:$(dark.bg);
--body-bg:$(body.background);
--outer-bg:$(dark1.bg);
--main-color:$(dark.main.color);
--title-color:$(dark.title);
--title-hover-color:$(dark.main.color);
--text-color:$(dark.text);
--meta-color:$(dark.meta);
--meta-link-color:$(dark.meta.link);
--topad-bg:$(dark1.bg);
--topad-border:transparent;
--header-bg:$(dark2.bg);
--header-color:$(dark.title);
--header-hover-color:$(dark.main.color);
--submenu-bg:$(dark3.bg);
--submenu-color:$(dark.title);
--submenu-hover-color:$(dark.main.color);
--mega-bg:$(dark3.bg);
--mega-color:$(dark.title);
--mega-hover-color:$(dark.main.color);
--mega-meta-color:$(dark.meta);
--mobilemenu-bg:$(dark1.bg);
--mobilemenu-color:$(dark.title);
--mobilemenu-hover-color:$(dark.main.color);
--ticker-bg:$(dark2.bg);
--ticker-icon:$(dark.main.color);
--ticker-title:$(dark.title);
--ticker-color:$(dark.text);
--ticker-hover-color:$(dark.main.color);
--ticker-border:$(dark.border);
--widget-bg:$(dark2.bg);
--footerad-bg:$(dark2.bg);
--footerad-border:$(dark.border);
--footer-bg:$(dark2.bg);
--footer-color:$(dark.title);
--footer-text-color:$(dark.text);
--footerbar-bg:$(dark1.bg);
--footerbar-color:$(dark.title);
--footerbar-hover-color:$(dark.main.color);
--footerbar-border-color:transparent;
--cookie-bg:$(dark2.bg);
--cookie-color:$(dark.text);
--gray-bg:rgba(255,255,255,0.03);
--border-color:$(dark.border);
}
html.rtl{
--body-font:'Cairo',Arial,sans-serif;
--menu-font:'Cairo',Arial,sans-serif;
--title-font:'Cairo',Arial,sans-serif;
--text-font:'Cairo',Arial,sans-serif;
}

/*-- Reset CSS --*/
html,body,a,abbr,acronym,address,applet,b,big,blockquote,caption,center,cite,code,dd,del,dfn,div,dl,dt,em,fieldset,font,form,input,button,h1,h2,h3,h4,h5,h6,i,iframe,img,ins,kbd,label,legend,li,object,p,pre,q,s,samp,small,span,strike,strong,sub,sup,table,tbody,td,tfoot,th,thead,tr,tt,u,ul,var{padding:0;margin:0;border:0;outline:none;vertical-align:baseline;background:0 0;text-decoration:none}dl,ul{list-style-position:inside;list-style:none}ul li{list-style:none}caption{text-align:center}img{border:none;position:relative}a,a:visited{text-decoration:none}.clearfix{clear:both}.section,.widget,.widget ul{margin:0;padding:0}a{color:var(--main-color)}a img{border:0}abbr{text-decoration:none}.separator a{text-decoration:none!important;clear:none!important;float:none!important;margin-left:0!important;margin-right:0!important}#Navbar1,#navbar-iframe,.widget-item-control,a.quickedit,.home-link,.feed-links{display:none!important}.center{display:table;margin:0 auto;position:relative}.widget > h2,.widget > h3{display:none}.widget iframe,.widget img{max-width:100%}button,input,select,textarea{background:transparent;font-family:var(--body-font);-webkit-appearance:none;-moz-appearance:none;appearance:none;outline:none;border-radius:0}button{cursor:pointer}input[type="search"]::-webkit-search-cancel-button{-webkit-appearance:none}

/*-- Main CSS --*/
*{box-sizing:border-box}
html{position:relative;word-break:break-word;word-wrap:break-word;text-rendering:optimizeLegibility;-webkit-font-smoothing:antialiased;-webkit-text-size-adjust:100%}
body{position:relative;background:var(--body-bg);background-color:var(--body-bg-color);font-family:var(--body-font);font-size:14px;color:var(--text-color);font-weight:400;font-style:normal;line-height:1.4em}
.rtl{direction:rtl}
h1,h2,h3,h4,h5,h6{font-family:var(--title-font);font-weight:700}
a,input,textarea,button{transition:all .0s ease}
#outer-wrapper{position:relative;overflow:hidden;width:100%;max-width:100%;background-color:var(--outer-bg);margin:0 auto;padding:0}
.is-boxed #outer-wrapper{width:$(row.width + 50px);max-width:100%;box-shadow:0 0 20px rgba(0,0,0,0.05)}
.is-dark .is-boxed #outer-wrapper{box-shadow:0 0 20px rgba(0,0,0,0.2)}
.container{position:relative}
.row-x1{width:$(row.width);max-width:100%}
.row-x2{width:100%}
.flex-c{display:flex;justify-content:center}
.flex-col{display:flex;flex-direction:column}
.flex-sb{display:flex;justify-content:space-between}
#content-wrapper{float:left;width:100%;overflow:hidden;padding:25px 0}
.is-left #content-wrapper > .container,.rtl .is-right #content-wrapper > .container{flex-direction:row-reverse}
.rtl .is-left #content-wrapper > .container{flex-direction:row}
.theiaStickySidebar:before,.theiaStickySidebar:after{content:'';display:table;clear:both}
#main-wrapper{position:relative;width:calc(100% - $(sidebar.width + 25px))}
.no-sidebar #main-wrapper{width:100%}
#sidebar-wrapper{position:relative;width:$(sidebar.width)}
.no-sidebar #sidebar-wrapper{display:none}
.entry-thumbnail,.entry-avatar,.comments .avatar-image-container{display:block;position:relative;overflow:hidden;background-color:var(--gray-bg);z-index:5;color:transparent}
.entry-thumbnail{border-radius:var(--radius)}
.thumbnail,.avatar{display:block;position:relative;width:100%;height:100%;background-size:cover;background-position:center center;background-repeat:no-repeat;z-index:1;transform-origin:center;opacity:0;transition:opacity .35s ease}
.thumbnail.pbt-lazy,.avatar.pbt-lazy{opacity:1}
.entry-thumbnail:hover .thumbnail,.cs:hover .entry-thumbnail .thumbnail{filter:brightness(1.03)}
.is-ytimg:after{position:absolute;content:'\e038';top:50%;right:50%;font-family:'Material Icons Round';font-size:56px;color:#fff;font-weight:400;z-index:5;transform:translate(50%,-50%);text-shadow:0 0 40px rgba(0,0,0,0.67);opacity:.8}
.sz-1.is-ytimg:after{transform:translate(50%,-50%) scale(1.15)}
.sz-2.is-ytimg:after{transform:translate(50%,-50%) scale(.9)}
.sz-3.is-ytimg:after{transform:translate(50%,-50%) scale(.75)}
.sz-4.is-ytimg:after{transform:translate(50%,-50%) scale(.65)}
.sz-5.is-ytimg:after{transform:translate(50%,-50%) scale(.45)}
.is-ytimg:hover:after,.cs:hover .is-ytimg:after{opacity:1}
.cs .is-ytimg:after{top:15px;right:15px;transform:translate(0)}
.rtl .cs .is-ytimg:after{left:15px;right:unset}
.entry-header{display:flex;flex-direction:column}
.entry-thumbnail .entry-category{display:-webkit-box;position:absolute;left:20px;bottom:20px;max-width:calc(100% - 40px);height:18px;background:var(--thumbtag-bg);overflow:hidden;font-size:10px;color:var(--thumbtag-color);font-weight:500;text-transform:uppercase;line-height:18px;-webkit-line-clamp:1;-webkit-box-orient:vertical;z-index:2;padding:0 8px;border-radius:var(--radius)}
.rtl .entry-thumbnail .entry-category{left:unset;right:20px}
.entry-header .entry-category{display:flex;font-size:13px;color:var(--entrytag-color);font-weight:600;margin:0 0 8px}
.entry-title{color:var(--title-color);font-weight:var(--title-weight);line-height:1.3em}
.entry-title a{display:block;color:var(--title-color)}
.entry-title a:hover{color:var(--title-hover-color)}
.entry-meta{display:flex;font-size:12px;color:var(--meta-color);font-weight:var(--light-weight);margin:4px 0 0}
.entry-meta .mi{display:flex}
.entry-meta .mi,.entry-meta .sp{margin:0 4px 0 0}
.rtl .entry-meta .mi,.rtl .entry-meta .sp{margin:0 0 0 4px}
.entry-meta .author-name{color:var(--meta-link-color);font-weight:600}
.excerpt{font-family:var(--text-font);line-height:1.5em;font-weight:var(--light-weight)}
.cs .entry-inner{display:block;position:relative;width:100%;height:100%;overflow:hidden}
.mask:before{content:'';position:absolute;left:0;right:0;bottom:0;height:80%;background-image:linear-gradient(to bottom,rgba(0,0,0,0) 25%,rgba(0,0,0,0.5));-webkit-backface-visibility:hidden;backface-visibility:hidden;z-index:2;opacity:1;margin:0;transition:opacity .25s ease}
.entry-info{position:absolute;left:0;bottom:0;width:100%;background:linear-gradient(to bottom,rgba(0,0,0,0),rgba(0,0,0,0.65));overflow:hidden;z-index:10;padding:15px}
.entry-info .entry-title{color:#fff;text-shadow:0 1px 2px rgba(0,0,0,0.2)}
.entry-info .entry-meta{color:#c5c5ca;text-shadow:0 1px 2px rgba(0,0,0,0.1)}
.entry-info .entry-meta .author-name{color:#d5d5da}
.entry-info .entry-category{width:-moz-fit-content;width:fit-content;margin:0 0 11px}
.btn{position:relative;border-radius:var(--radius)}
.error-msg{display:flex;align-items:center;font-size:14px;color:var(--meta-color);padding:20px 0;font-weight:400}
.loader{position:relative;width:100%;height:100%;overflow:hidden;display:flex;align-items:center;justify-content:center;margin:0}
.loader:after{content:'';display:block;width:30px;height:30px;box-sizing:border-box;margin:0;border:2px solid var(--main-color);border-right-color:var(--gray-bg);border-radius:100%;animation:spinner .65s infinite linear;transform-origin:center}
@keyframes spinner{0%{-webkit-transform:rotate(0deg);transform:rotate(0deg)}to{-webkit-transform:rotate(1turn);transform:rotate(1turn)}}
.overlay{visibility:hidden;opacity:0;position:fixed;top:0;left:0;right:0;bottom:0;background-color:rgba(22,22,26,0.5);z-index:1000;margin:0;transition:all .25s ease}
.social a:before{display:block;font-family:'Font Awesome 5 Brands';font-style:normal;font-weight:400}
.social .rss a:before,.social .share a:before,.social .email a:before,.social .external-link a:before{content:'\e0e5';font-family:'Material Icons Round'}
.social .share a:before{content:'\e80d'}
.social .email a:before{content:'\e0be'}
.social .external-link a:before{content:'\e89e'}
.sb-a .google a,.sb-h .google a:hover{background-color:#1a73e8}
.sb-a .blogger a,.sb-h .blogger a:hover{background-color:#ff5722}
.sb-a .apple a,.sb-h .apple a:hover{background-color:#333}
.sb-a .amazon a,.sb-h .amazon a:hover{background-color:#fe9800}
.sb-a .microsoft a,.sb-h .microsoft a:hover{background-color:#0067B8}
.sb-a .facebook a,.sb-a .facebook-f a,.sb-h .facebook a:hover,.sb-h .facebook-f a:hover{background-color:#3b5999}
.sb-a .twitter a,.sb-h .twitter a:hover{background-color:#00acee}
.sb-a .youtube a,.sb-h .youtube a:hover{background-color:#e60023}
.sb-a .instagram a,.sb-h .instagram a:hover{background:linear-gradient(15deg,#ffb13d,#dd277b,#4d5ed4)}
.sb-a .pinterest a,.sb-a .pinterest-p a,.sb-h .pinterest a:hover,.sb-h .pinterest-p a:hover{background-color:#e60023}
.sb-a .dribbble a,.sb-h .dribbble a:hover{background-color:#ea4c89}
.sb-a .linkedin a,.sb-h .linkedin a:hover{background-color:#0077b5}
.sb-a .tumblr a,.sb-h .tumblr a:hover{background-color:#365069}
.sb-a .twitch a,.sb-h .twitch a:hover{background-color:#6441a5}
.sb-a .rss a,.sb-h .rss a:hover{background-color:#ffc200}
.sb-a .skype a,.sb-h .skype a:hover{background-color:#00aff0}
.sb-a .stumbleupon a,.sb-h .stumbleupon a:hover{background-color:#eb4823}
.sb-a .vk a,.sb-h .vk a:hover{background-color:#4a76a8}
.sb-a .stack-overflow a,.sb-h .stack-overflow a:hover{background-color:#f48024}
.sb-a .github a,.sb-h .github a:hover{background-color:#24292e}
.sb-a .soundcloud a,.sb-h .soundcloud a:hover{background:linear-gradient(#ff7400,#ff3400)}
.sb-a .behance a,.sb-h .behance a:hover{background-color:#191919}
.sb-a .digg a,.sb-h .digg a:hover{background-color:#1b1a19}
.sb-a .delicious a,.sb-h .delicious a:hover{background-color:#0076e8}
.sb-a .codepen a,.sb-h .codepen a:hover{background-color:#000}
.sb-a .flipboard a,.sb-h .flipboard a:hover{background-color:#f52828}
.sb-a .reddit a,.sb-h .reddit a:hover{background-color:#ff4500}
.sb-a .whatsapp a,.sb-h .whatsapp a:hover{background-color:#3fbb50}
.sb-a .messenger a,.sb-h .messenger a:hover{background-color:#0084ff}
.sb-a .snapchat a,.sb-h .snapchat a:hover{background-color:#ffe700}
.sb-a .telegram a,.sb-h .telegram a:hover{background-color:#179cde}
.sb-a .steam a,.sb-h .steam a:hover{background:linear-gradient(5deg,#0d89bc,#112c5b,#0d1c47)}
.sb-a .discord a,.sb-h .discord a:hover{background-color:#7289da}
.sb-a .quora a,.sb-h .quora a:hover{background-color:#b92b27}
.sb-a .tiktok a,.sb-h .tiktok a:hover{background-color:#fe2c55}
.sb-a .share a,.sb-h .share a:hover{background-color:var(--meta-color)}
.sb-a .email a,.sb-h .email a:hover{background-color:#888}
.sb-a .external-link a,.sb-h .external-link a:hover{background-color:var(--title-color)}
.sc-a .blogger a,.sc-h .blogger a:hover{color:#1a73e8}
.sc-a .blogger a,.sc-h .blogger a:hover{color:#ff5722}
.sc-a .apple a,.sc-h .apple a:hover{color:#333}
.sc-a .amazon a,.sc-h .amazon a:hover{color:#fe9800}
.sc-a .microsoft a,.sc-h .microsoft a:hover{color:#0067B8}
.sc-a .facebook a,.sc-a .facebook-f a,.sc-h .facebook a:hover,.sc-h .facebook-f a:hover{color:#3b5999}
.sc-a .twitter a,.sc-h .twitter a:hover{color:#00acee}
.sc-a .youtube a,.sc-h .youtube a:hover{color:#e60023}
.sc-a .instagram a,.sc-h .instagram a:hover{color:#dd277b}
.sc-a .pinterest a,.sc-a .pinterest-p a,.sc-h .pinterest a:hover,.sc-h .pinterest-p a:hover{color:#e60023}
.sc-a .dribbble a,.sc-h .dribbble a:hover{color:#ea4c89}
.sc-a .linkedin a,.sc-h .linkedin a:hover{color:#0077b5}
.sc-a .tumblr a,.sc-h .tumblr a:hover{color:#365069}
.sc-a .twitch a,.sc-h .twitch a:hover{color:#6441a5}
.sc-a .rss a,.sc-h .rss a:hover{color:#ffc200}
.sc-a .skype a,.sc-h .skype a:hover{color:#00aff0}
.sc-a .stumbleupon a,.sc-h .stumbleupon a:hover{color:#eb4823}
.sc-a .vk a,.sc-h .vk a:hover{color:#4a76a8}
.sc-a .stack-overflow a,.sc-h .stack-overflow a:hover{color:#f48024}
.sc-a .github a,.sc-h .github a:hover{color:#24292e}
.sc-a .soundcloud a,.sc-h .soundcloud a:hover{color:#ff7400}
.sc-a .behance a,.sc-h .behance a:hover{color:#191919}
.sc-a .digg a,.sc-h .digg a:hover{color:#1b1a19}
.sc-a .delicious a,.sc-h .delicious a:hover{color:#0076e8}
.sc-a .codepen a,.sc-h .codepen a:hover{color:#000}
.sc-a .flipboard a,.sc-h .flipboard a:hover{color:#f52828}
.sc-a .reddit a,.sc-h .reddit a:hover{color:#ff4500}
.sc-a .whatsapp a,.sc-h .whatsapp a:hover{color:#3fbb50}
.sc-a .messenger a,.sc-h .messenger a:hover{color:#0084ff}
.sc-a .snapchat a,.sc-h .snapchat a:hover{color:#ffe700}
.sc-a .telegram a,.sc-h .telegram a:hover{color:#179cde}
.sc-a .steam a,.sc-h .steam a:hover{color:#112c5b}
.sc-a .discord a,.sc-h .discord a:hover{color:#7289da}
.sc-a .quora a,.sc-h .quora a:hover{color:#b92b27}
.sc-a .tiktok a,.sc-h .tiktok a:hover{color:#fe2c55}
.sc-a .share a,.sc-h .share a:hover{color:var(--meta-color)}
.sc-a .email a,.sc-h .email a:hover{color:#888}
.sc-a .external-link a,.sc-h .external-link a:hover{color:var(--title-color)}
#top-ads-wrap{position:relative;float:left;width:100%;background-color:var(--topad-bg);margin:0}
#top-ads-wrap.has-border{border-bottom:1px solid var(--topad-border)}
#top-ads-wrap .widget{padding:15px 0}
#header-wrapper{float:left;width:100%;z-index:50}
.main-header,.header-inner,.header-header{float:left;width:100%;height:$(header.height);background:var(--header-bg)}
.header-inner{background:rgba(0,0,0,0)}
.header-header{box-shadow:var(--widget-shadow)}
.header-inner.is-fixed .header-header{box-shadow:0 1px 8px rgba(0,0,0,0.1)}
.header-inner.is-fixed{position:fixed;top:-$(header.height * 2);left:0;width:100%;z-index:990;backface-visibility:hidden;visibility:hidden;opacity:0;transform:translate3d(0,0,0);transition:all .25s ease}
.header-inner.is-fixed.show{visibility:visible;opacity:1;transform:translate3d(0,$(header.height * 2),0)}
.is-boxed .header-header{float:none;width:$(row.width + 50px);max-width:100%;margin:0 auto;padding:0}
.header-items{position:relative;display:flex;flex-wrap:wrap;justify-content:space-between;--search-width:$(sidebar.width)}
.flex-left{display:flex;align-items:center;z-index:15}
.flex-right{display:flex;align-items:center;position:absolute;top:0;right:0;height:$(header.height);z-index:15;transition:all .17s ease}
.rtl .flex-right{left:0;right:unset}
.main-logo{display:flex;align-items:center;flex-shrink:0;height:$(header.height);overflow:hidden;margin:0 28px 0 0}
.rtl .main-logo{margin:0 0 0 28px}
.main-logo img{display:block;width:auto;height:auto;max-height:40px}
.main-logo .title{max-width:100%;font-size:25px;color:var(--header-color);line-height:40px;font-weight:700;overflow:hidden;white-space:nowrap;text-overflow:ellipsis}
.main-logo .title a{color:var(--header-color)}
.main-logo .title a:hover{color:var(--header-hover-color)}
.main-logo #h1-off{display:none;visibility:hidden}
#buzzspot-pro-main-menu{z-index:10;transition:all .17s ease}
#buzzspot-pro-main-menu .widget,#buzzspot-pro-main-menu .widget > .widget-title{display:none}
#buzzspot-pro-main-menu .show-menu{display:block}
.main-nav{display:flex;height:$(header.height)}
.main-nav > li{position:relative;display:flex;flex-shrink:0}
.main-nav > li + li{margin:0 0 0 28px}
.rtl .main-nav > li + li{margin:0 28px 0 0}
.main-nav > li > a{display:flex;font-family:var(--menu-font);font-size:15px;color:var(--header-color);font-weight:700;align-items:center}
.main-nav > li:hover > a{color:var(--header-hover-color)}
.main-nav .has-sub > a:after{display:inline-block;content:'\e5cf';font-family:'Material Icons Round';font-size:16px;font-weight:400;margin:-4px 0 0 2px}
.rtl .main-nav .has-sub > a:after{margin:-4px 2px 0 0}
.main-nav .sub-menu,.main-nav .ul{position:absolute;left:0;top:$(header.height);width:180px;background-color:var(--submenu-bg);z-index:99999;padding:6px 0;border-radius:var(--radius);backface-visibility:hidden;visibility:hidden;opacity:0;box-shadow:0 1px 2px rgba(0,0,0,0.05),0 5px 10px 0 rgba(0,0,0,0.05)}
.rtl .main-nav .sub-menu,.rtl .main-nav .ul{left:auto;right:0}
.main-nav .sub-menu.sm-1{left:-14px}
.rtl .main-nav .sub-menu.sm-1{left:unset;right:-14px}
.main-nav .sub-menu.sm-2{top:-6px;left:100%}
.rtl .main-nav .sub-menu.sm-2{left:unset;right:100%}
.main-nav .sub-menu li{position:relative;display:block}
.main-nav .sub-menu li a{display:flex;justify-content:space-between;font-size:14px;color:var(--submenu-color);padding:8px 15px}
.main-nav .sub-menu li:hover > a{color:var(--submenu-hover-color)}
.main-nav .sub-menu > .has-sub > a:after{content:'\e5cc';margin:0 -5px}
.rtl .main-nav .sub-menu > .has-sub > a:after{content:'\e5cb'}
.main-nav .sub-menu,.main-nav .ul{transition:all .17s ease}
.main-nav li:hover > .sub-menu,.main-nav li:hover .ul{backface-visibility:inherit;visibility:visible;opacity:1}
.main-nav .mega-menu{position:static!important}
.main-nav .mega-menu > .ul{width:100%;background-color:var(--mega-bg);overflow:hidden}
.mega-menu .mega-items{display:grid;grid-template-columns:repeat(5,1fr);column-gap:20px;padding:20px}
.mega-items .post{--title-color:var(--mega-color);--title-hover-color:var(--mega-hover-color);--meta-color:var(--mega-meta-color);width:100%;display:flex;flex-direction:column}
.mega-items .entry-thumbnail{width:100%;height:126px;z-index:1;margin:0 0 8px}
.mega-items .entry-title{font-size:14px}
.mega-menu .mega-items.on-load,.mega-menu .mega-items.no-items{grid-template-columns:1fr}
.mega-menu .error-msg{justify-content:center;padding:40px 0}
.mega-menu .loader{height:120px}
.mobile-menu-toggle{display:none;height:34px;font-size:26px;color:var(--header-color);align-items:center;padding:0 13px 0 16px}
.rtl .mobile-menu-toggle{padding:0 16px 0 13px}
.mobile-menu-toggle:after{content:'\e5d2';font-family:'Material Icons Round';font-weight:400}
.mobile-menu-toggle:hover{color:var(--header-hover-color)}
.toggle-wrap{display:flex;align-items:center;z-index:20}
@-webkit-keyframes darkOff{0%{transform:scale(.7);opacity:.25}100%{transform:scale(1);opacity:1}}
@-webkit-keyframes darkOn{0%{transform:scale(.7);opacity:.25}100%{transform:scale(1);opacity:1}}
.darkmode-toggle{display:flex;align-items:center;justify-content:center;width:34px;height:34px;font-size:16px;color:var(--header-color);transform-origin:center;margin:0 5px 0 0}
.rtl .darkmode-toggle{margin:0 0 0 5px}
.darkmode-toggle:before{display:block;content:'\ea46';font-family:'PBT Icons';font-weight:400;line-height:0}
.is-dark .darkmode-toggle:before{content:'\e518'}
.darkmode-toggle:hover{color:var(--header-hover-color)}
.darkmode-toggle.dark-off{animation:darkOff .35s ease}
.darkmode-toggle.dark-on{animation:darkOn .35s ease}
.search-toggle{display:flex;align-items:center;justify-content:center;width:34px;height:34px;background-color:var(--gray-bg);color:var(--header-color);font-size:24px}
.search-toggle:before{display:block;content:'\e8b6';font-family:'Material Icons Round';font-weight:400}
.search-toggle:hover{color:var(--header-hover-color)}
@-webkit-keyframes showSearch{0%{width:95%;opacity:0}100%{width:100%;opacity:1}}
#main-search-wrap{display:none;position:absolute;top:0;right:0;width:var(--search-width);height:$(header.height);z-index:25;transition:all 0s ease}
.rtl #main-search-wrap{left:0;right:unset}
.main-search{position:relative;float:right;width:100%;height:100%;display:flex;align-items:center;animation:showSearch .17s ease}
.rtl .main-search{float:left}
.main-search .search-form{display:flex;flex:1;height:34px}
.main-search .search-input{width:100%;flex:1;font-family:inherit;font-size:16px;color:var(--header-color);font-weight:var(--light-weight);text-align:left}
.rtl .main-search .search-input{text-align:right}
.main-search .search-input::placeholder{color:var(--header-color);opacity:.65;outline:none}
.main-search .search-toggle:before{content:'\e5cd'}
.search-active .buzzspot-pro-main-menu,.search-active .flex-right{visibility:hidden;opacity:0}
#slide-menu{display:none;position:fixed;width:300px;height:100%;top:0;left:0;bottom:0;background-color:var(--mobilemenu-bg);overflow:hidden;z-index:1010;left:0;-webkit-transform:translate3d(-100%,0,0);transform:translate3d(-100%,0,0);visibility:hidden;box-shadow:3px 0 10px rgba(0,0,0,0.1);transition:all .25s ease}
.rtl #slide-menu{left:unset;right:0;-webkit-transform:translate3d(100%,0,0);transform:translate3d(100%,0,0)}
.nav-active #slide-menu,.rtl .nav-active #slide-menu{-webkit-transform:translate3d(0,0,0);transform:translate3d(0,0,0);visibility:visible}
.slide-menu-header{height:$(header.height);background:var(--header-bg);overflow:hidden;display:flex;align-items:center;justify-content:space-between;box-shadow:0 1px 8px rgba(0,0,0,0.1)}
.mobile-logo{display:flex;flex:1;width:100%;overflow:hidden;padding:0 0 0 20px}
.rtl .mobile-logo{padding:0 20px 0 0}
.mobile-logo .homepage{max-width:100%;font-size:25px;color:var(--header-color);line-height:40px;font-weight:700;overflow:hidden;white-space:nowrap;text-overflow:ellipsis}
.mobile-logo .homepage:hover{color:var(--header-hover-color)}
.mobile-logo .logo-img img{display:block;width:auto;max-width:100%;height:auto;max-height:40px}
.hide-mobile-menu{display:flex;height:100%;color:var(--header-color);font-size:26px;align-items:center;z-index:20;padding:0 15px}
.hide-mobile-menu:before{content:'\e5cd';font-family:'Material Icons Round';font-weight:400}
.hide-mobile-menu:hover{color:var(--header-hover-color)}
.slide-menu-flex{display:flex;height:calc(100% - $(header.height));flex-direction:column;justify-content:space-between;overflow:hidden;overflow-y:auto;-webkit-overflow-scrolling:touch}
.mobile-menu{padding:20px}
.mobile-menu .sub-menu{display:none;grid-column:1/3;overflow:hidden}
.mobile-menu ul li a{display:block;font-size:14px;color:var(--mobilemenu-color);font-weight:400;padding:10px 0}
.mobile-menu > ul > li > a{font-family:var(--menu-font);font-weight:700;text-transform:uppercase}
.mobile-menu li.has-sub{display:grid;grid-template-columns:1fr 30px}
.mobile-menu .submenu-toggle{display:flex;align-items:center;justify-content:center;align-self:center;height:30px;background-color:var(--gray-bg);font-size:24px;color:var(--mobilemenu-color)}
.mobile-menu .submenu-toggle:before{content:'\e5cf';font-family:'Material Icons Round';font-weight:400}
.mobile-menu .expanded > .submenu-toggle:before{content:'\e5ce'}
.mobile-menu ul li a:hover,.mobile-menu .submenu-toggle:hover{color:var(--mobilemenu-hover-color)}
.mobile-menu li.has-sub li a{font-size:14px;opacity:.75;padding:10px 15px}
.mobile-menu li.has-sub li li a{padding:10px 30px}
.mm-footer{padding:20px}
.mm-footer ul{display:flex;flex-wrap:wrap}
.mm-footer li{margin:0 15px 0 0}
.rtl .mm-footer li{margin:0 0 0 15px}
.mm-footer li:last-child{margin:0}
.mm-footer .link-list{margin:10px 0 0}
.mm-footer .link-list li{margin-top:5px}
.mm-footer a{display:block;font-size:14px;color:var(--mobilemenu-color)}
.mm-footer .rss a,.mm-footer .email a,.mm-footer .external-link a{font-size:18px}
.mm-footer .social a:hover{opacity:.9}
.mm-footer .link-list a:hover{color:var(--mobilemenu-hover-color)}
#ticker-wrapper{position:relative;float:left;width:100%;background-color:var(--ticker-bg);box-shadow:var(--widget-shadow)}
#ticker-wrapper.has-border,.is-dark #ticker-wrapper{border-top:1px solid var(--ticker-border)}
#ticker .widget{display:none;align-items:center;height:34px;margin:0}
#ticker .widget.is-visible,#ticker .widget.PopularPosts{display:flex}
.ticker .widget-title{display:flex;align-items:center;position:relative;margin:0 6px 0 0}
.rtl .ticker .widget-title{margin:0 0 0 6px}
.ticker .widget-title:before{display:inherit;content:'\e932';font-family:'Material Icons Round';font-size:15px;color:var(--ticker-icon);font-weight:400;line-height:1}
.ticker .widget-title .title{display:flex;align-items:center;font-size:15px;color:var(--ticker-title);font-weight:700;margin:0 0 0 3px}
.rtl .ticker .widget-title .title{margin:0 3px 0 0}
.ticker .widget-title .title:after{display:inline-block;content:'\e5cc';font-family:'Material Icons Round';font-weight:400;font-size:16px;line-height:1;margin:1px -2px 0}
.rtl .ticker .widget-title .title:after{content:'\e5cb'}
.ticker .widget-content{display:flex;justify-content:space-between;flex:1}
.ticker .loader{justify-content:flex-start;padding:0 1px}
.ticker .loader:after{width:14px;height:14px;border-width:1.5px}
.ticker .error-msg{max-width:100%;overflow:hidden;white-space:nowrap;text-overflow:ellipsis;padding:0}
.ticker-items{position:relative;flex:1;overflow:hidden}
.ticker-items .post{position:absolute;top:0;left:0;width:100%;opacity:0;visibility:hidden;transform:translate3d(5px,0,0);pointer-events:none;transition:all .85s ease}
.rtl .ticker-items .post{left:unset;right:0;transform:translate3d(-10px,0,0)}
.ticker-items .post.active{opacity:1;visibility:visible;transform:translate3d(0,0,0);pointer-events:initial}
.ticker-items .entry-title{display:flex;align-items:center;height:20px;font-size:14px;font-weight:400}
.ticker-items .entry-title a{max-width:100%;overflow:hidden;color:var(--ticker-color);white-space:nowrap;text-overflow:ellipsis}
.ticker-items .entry-title a:hover{color:var(--ticker-hover-color)}
.ticker-nav{display:grid;grid-template-columns:repeat(2,1fr);grid-gap:5px;padding:0 0 0 10px}
.rtl .ticker-nav{padding:0 10px 0 0}
.ticker-nav button{display:flex;width:20px;height:20px;background-color:var(--gray-bg);font-size:18px;color:var(--ticker-title);align-items:center;justify-content:center}
.ticker-nav button:hover{color:var(--ticker-hover-color)}
.ticker-nav button:before{display:block;font-family:'Material Icons Round'}
.ticker-nav .tn-prev:before,.rtl .ticker-nav .tn-next:before{content:'\e5cb'}
.ticker-nav .tn-next:before,.rtl .ticker-nav .tn-prev:before{content:'\e5cc'}
#trending-wrapper,#trending .widget,#trending .widget-content{float:left;width:100%;margin:0}
#trending .widget{display:none;margin:25px 0 0}
#trending .widget.is-visible,#trending .widget.PopularPosts{display:block}
#trending .widget-content{display:flex;align-items:center;justify-content:center;min-height:289.33px;margin:0}
#trending .PopularPosts .widget-content{min-height:unset}
#trending .error-msg{padding:0}
.trending-items{width:100%;display:grid;grid-template-columns:repeat(4,1fr);grid-gap:25px}
.trending-items .post{display:flex;flex-direction:column;position:relative;width:100%;background-color:var(--widget-bg);overflow:hidden;z-index:10;border-radius:var(--radius);box-shadow:var(--widget-shadow)}
.trending-items .entry-thumbnail{width:100%;height:160px;border-radius:0}
.trending-items .entry-header{padding:18px 20px 20px}
.trending-items .entry-title{font-size:17px}
.trending-items .entry-meta{flex-wrap:wrap;margin:6px 0 0}
.main-title-wrap{display:flex;align-items:center;justify-content:space-between;margin:0 0 20px}
.main-title-wrap > .title{display:flex;align-items:center;position:relative;font-size:17px;color:var(--title-color);line-height:1;margin:0}
.main-title-wrap > .title:after{display:inline-block;content:'\e5cc';font-family:'Material Icons Round';font-size:20px;color:var(--main-color);font-weight:400;line-height:0;margin:3px 0 0 -3px}
.rtl .main-title-wrap > .title:after{content:'\e5cb';margin: 3px -3px 0 0}
.main-title-wrap > .title-link{font-size:14px;color:var(--meta-color);line-height:1;font-weight:var(--light-weight)}
.main-title-wrap > .title-link:hover{color:var(--main-color)}
.featured{float:left;width:100%}
.featured .widget{margin:0 0 25px}
.featured-post{display:flex;flex-direction:column;position:relative;background-color:var(--widget-bg);overflow:hidden;z-index:10;border-radius:var(--radius);box-shadow:var(--widget-shadow)}
.featured-post .entry-thumbnail{width:100%;height:320px;border-radius:0}
.featured-post .entry-header{padding:20px}
.featured-post .entry-title{font-size:25px}
.featured-post .entry-excerpt{font-size:1.022em;margin:10px 0 0}
.featured-post .entry-meta{flex-wrap:wrap;font-size:14px;margin:10px 0 0}
.home-ads{float:left;width:100%}
.home-ads .widget{margin:0 0 25px}
.list-items{display:grid;grid-template-columns:1fr;grid-gap:25px}
.list-items .post{display:flex;position:relative;background-color:var(--widget-bg);overflow:hidden;z-index:10;border-radius:var(--radius);box-shadow:var(--widget-shadow)}
.list-items .entry-thumbnail{width:320px;max-width:50%;height:192px;min-height:100%;border-radius:0}
.list-items .entry-header{flex:1;align-self:center;padding:18px}
.list-items .entry-title{font-size:21px}
.list-items .entry-excerpt{font-size:14px;margin:6px 0 0}
.list-items .entry-meta{flex-wrap:wrap;margin:8px 0 0}
.grid-items{display:grid;grid-template-columns:repeat(2,1fr);grid-gap:25px}
.grid-items .post{display:flex;flex-direction:column;position:relative;background-color:var(--widget-bg);overflow:hidden;z-index:10;border-radius:var(--radius);box-shadow:var(--widget-shadow)}
.grid-items .entry-thumbnail{width:100%;height:180px;border-radius:0}
.grid-items .entry-header{padding:20px}
.grid-items .entry-title{font-size:21px}
.grid-items .entry-excerpt{display:-webkit-box;font-size:14px;overflow:hidden;-webkit-line-clamp:2;-webkit-box-orient:vertical;margin:6px 0 0}
.grid-items .entry-meta{flex-wrap:wrap;margin:8px 0 0}
#main,.index-blog{float:left;width:100%}
.queryMessage .query-info{display:flex;align-items:center;font-family:var(--title-font);font-size:17px;color:var(--title-color);font-weight:var(--title-weight);margin:0 0 20px}
.no-posts .queryMessage .query-info{margin:0}
.queryMessage .query-info:after{display:inline-block;content:'\e5cc';font-family:'Material Icons Round';font-size:20px;color:var(--main-color);font-weight:400;line-height:0;margin:3px 0 0 -3px}
.rtl .queryMessage .query-info:after{content:'\e5cb';margin:3px -3px 0 0}
.queryEmpty{font-size:14px;color:var(--meta-color);text-align:center;margin:50px 0}
.index-post-wrap .post.ad-type{display:block;background:transparent;overflow:visible;border-radius:0;box-shadow:none}
@keyframes postFadeInUp{0%{opacity:0;transform:translate3d(0,10px,0)}100%{opacity:1;transform:translate3d(0,0,0)}}
.index-post-wrap .post.fadeInUp{animation:postFadeInUp .5s ease}
.item-post-inner{background-color:var(--widget-bg);border-radius:var(--radius);box-shadow:var(--widget-shadow)}
#breadcrumb{display:flex;font-size:14px;color:var(--meta-color);font-weight:var(--light-weight);line-height:1;margin:0 0 10px}
#breadcrumb a{color:var(--meta-color)}
#breadcrumb a.home,#breadcrumb a:hover{color:var(--main-color)}
#breadcrumb .separator:after{content:'\e5cc';font-family:'Material Icons Round';font-size:16px;font-weight:400;font-style:normal;vertical-align:middle}
.rtl #breadcrumb .separator:after{content:'\e5cb'}
.item-post h1.entry-title{font-size:$(itempost.title.size)}
.entry-header.p-eh{padding:20px;border-bottom:1px solid var(--border-color)}
.p-eh .entry-meta{justify-content:space-between;font-size:14px;margin:13px 0 0}
.entry-meta .align-left,.entry-meta .align-right{display:flex;align-items:center}
.p-eh .entry-meta .mi,.p-eh .entry-meta .sp{margin:0 4px 0 0}
.rtl .entry-meta .mi,.rtl .p-eh .entry-meta .sp{margin:0 0 0 4px}
.entry-meta .entry-avatar{width:32px;height:32px;background-color:var(--widget-bg);overflow:hidden;padding:1px;margin:0 5px 0 0;border:1px solid var(--main-color);border-radius:50%}
.rtl .entry-meta .entry-avatar{margin:0 0 0 5px}
.entry-meta .avatar{z-index:2;border-radius:50%}
.entry-meta .al-items{display:flex}
.share-toggle{display:flex;align-items:center;justify-content:center;width:32px;height:32px;background-color:var(--gray-bg);color:var(--title-color);font-size:18px;border-radius:var(--radius)}
.share-toggle:before{display:block;content:'\e80d';font-family:'Material Icons Round';line-height:0;font-weight:400}
.rtl .share-toggle:before{transform:rotate3d(0,1,0,180deg)}
.share-toggle:hover{color:var(--title-hover-color)}
.entry-content-wrap{padding:20px}
#post-body{position:relative;float:left;width:100%;font-family:var(--text-font);font-size:$(itempost.content.size);color:var(--text-color);line-height:1.6em}
.post-body p{margin-bottom:25px}
.post-body h1,.post-body h2,.post-body h3,.post-body h4,.post-body h5,.post-body h6{font-size:17px;color:var(--title-color);line-height:1.3em;margin:0 0 20px}
.post-body h1{font-size:26px}
.post-body h2{font-size:23px}
.post-body h3{font-size:20px}
.post-body img{height:auto!important}
blockquote{position:relative;background-color:var(--gray-bg);color:var(--title-color);font-style:normal;padding:20px;margin:0;border-radius:var(--radius)}
blockquote:before{position:absolute;top:0;left:5px;content:'\e244';font-family:'Material Icons Round';font-size:60px;color:var(--title-color);font-style:normal;font-weight:400;line-height:1;opacity:.05;margin:0}
.rtl blockquote:before{left:unset;right:5px}
.post-body ul{padding:0 0 0 20px;margin:10px 0}
.rtl .post-body ul{padding:0 20px 0 0}
.post-body li{margin:8px 0;padding:0}
.post-body ul li,.post-body ol ul li{list-style:none}
.post-body ul li:before,.post-body ul li ul li ul li:before{display:inline-block;content:'\ef4a';font-family:'Material Icons Round';font-size:.4em;line-height:1;vertical-align:middle;margin:0 5px 0 0}
.post-body ul li ul li:before{content:'\e57b'}
.rtl .post-body ul li:before{margin:0 0 0 5px}
.post-body ol{counter-reset:pbt;padding:0 0 0 20px;margin:10px 0}
.rtl .post-body ol{padding:0 20px 0 0}
.post-body ol > li{counter-increment:pbt;list-style:none}
.post-body ol > li:before{display:inline-block;content:counters(pbt,'.')'.';margin:0 5px 0 0}
.rtl .post-body ol > li:before{margin:0 0 0 5px}
.post-body u{text-decoration:underline}
.post-body strike{text-decoration:line-through}
.post-body sup{vertical-align:super}
.post-body a{color:var(--main-color)}
.post-body a:hover{text-decoration:underline}
.post-body a.button{display:inline-block;height:34px;background:var(--button-bg);font-family:var(--body-font);font-size:15px;color:var(--button-color);font-weight:400;line-height:34px;text-align:center;text-decoration:none;cursor:pointer;padding:0 20px;margin:0 6px 8px 0}
.rtl .post-body a.button{margin:0 0 8px 6px}
.post-body a.button.x2{height:46px;font-size:18px;line-height:46px}
.post-body a.button.is-c,.rtl.post-body a.button.is-c{margin:0 3px 8px}
.post-body a.button.x2 span{display:inline-block;background-color:rgba(255,255,255,0.1);font-size:14px;line-height:14px;padding:6px;margin:0 0 0 20px;border-radius:var(--radius)}
.rtl .post-body a.button.x2 span{margin:0 20px 0 0}
.post-body .button:before{display:inline-block;font-family:'Material Icons Round';font-size:16px;font-weight:400;line-height:1;vertical-align:middle;margin:-1px 6px 0 0}
.rtl .post-body .button:before{margin:-1px 0 0 6px}
.post-body a.btn.x2:before{font-size:20px;margin:-2px 6px 0 0}
.rtl .post-body a.btn.x2:before{margin:-2px 0 0 6px}
.post-body .btn.preview:before{content:'\e8f4'}
.post-body .btn.download:before{content:'\f090'}
.post-body .btn.link:before{content:'\e157'}
.post-body .btn.cart:before{content:'\e8cc'}
.post-body .btn.info:before{content:'\e88e'}
.post-body .btn.share:before{content:'\e80d'}
.post-body .btn.contact:before{content:'\e0e1'}
.post-body .btn.whatsapp:before{content:'\f232';font-family:'Font Awesome 5 Brands';font-style:normal}
.post-body .btn.paypal:before{content:'\f1ed';font-family:'Font Awesome 5 Brands';font-style:normal}
.post-body .btn.gift:before{content:'\e8f6'}
.post-body a.color{color:#fff}
.post-body a.button:hover{opacity:.9}
.alert-message{display:block;background-color:var(--gray-bg);padding:20px;border:1px solid var(--border-color);border-radius:var(--radius)}
.alert-message.alert-success{background-color:rgba(39,174,96,0.1);color:rgba(39,174,96,1);border-color:rgba(39,174,96,0.1)}
.alert-message.alert-info{background-color:rgba(41,128,185,0.1);color:rgba(41,128,185,1);border-color:rgba(41,128,185,0.1)}
.alert-message.alert-warning{background-color:rgba(243,156,18,0.1);color:rgba(243,156,18,1);border-color:rgba(243,156,18,0.1)}
.alert-message.alert-error{background-color:rgba(231,76,60,0.1);color:rgba(231,76,60,1);border-color:rgba(231,76,60,0.1)}
.alert-message:before{display:inline-block;font-family:'Material Icons Round';font-size:18px;line-height:1;font-weight:400;vertical-align:middle;margin:0 5px 0 0}
.rtl .alert-message:before{margin:0 0 0 5px}
.alert-message.alert-success:before{content:'\e86c'}
.alert-message.alert-info:before{content:'\e88e'}
.alert-message.alert-warning:before{content:'\e000'}
.alert-message.alert-error:before{content:'\e5c9'}
.post-body table{width:100%;overflow-x:auto;text-align:left;margin:0;border-collapse:collapse;border:1px solid var(--border-color)}
.rtl .post-body table{text-align:right}
.post-body table td,.post-body table th{padding:6px 12px;border:1px solid var(--border-color)}
.post-body table thead th{color:var(--title-color);vertical-align:bottom}
table.tr-caption-container,table.tr-caption-container td,table.tr-caption-container th{line-height:1;padding:0;border:0}
table.tr-caption-container td.tr-caption{font-size:12px;color:var(--meta-color);font-style:italic;padding:6px 0 0}
.pbt-toc-wrap{display:flex;width:100%;clear:both;margin:0}
.pbt-toc-inner{position:relative;max-width:100%;background-color:var(--gray-bg);display:flex;flex-direction:column;overflow:hidden;font-size:14px;color:var(--title-color);line-height:1.6em;border:1px solid var(--border-color);border-radius:var(--radius)}
.pbt-toc-title{position:relative;height:40px;font-size:16px;color:var(--title-color);font-weight:var(--title-weight);display:flex;align-items:center;justify-content:space-between;padding:0 13px 0 18px}
.rtl .pbt-toc-title{padding:0 18px 0 13px}
.pbt-toc-title-text{display:flex}
.pbt-toc-title-text:before{content:'\e242';font-family:'Material Icons Round';font-size:20px;font-weight:400;margin:0 6px 0 0}
.rtl .pbt-toc-title-text:before{margin:0 0 0 6px}
.pbt-toc-title:after{content:'\e5cf';font-family:'Material Icons Round';font-size:24px;font-weight:400;margin:0 0 0 20px}
.rtl .pbt-toc-title:after{margin:0 20px 0 0}
.pbt-toc-title.is-expanded:after{content:'\e5ce'}
#pbt-toc{display:none;padding:0 20px 10px;margin:0}
#pbt-toc ol{counter-reset:pbtToc;padding:0 0 0 20px}
.rtl #pbt-toc ol{padding:0 20px 0 0}
#pbt-toc li{counter-increment:pbtToc;font-size:14px;margin:10px 0}
#pbt-toc li:before{content:counters(pbtToc,'.')'.'}
#pbt-toc li a{color:var(--main-color)}
#pbt-toc li a:hover{text-decoration:underline}
.post-body .contact-form-widget{display:table;width:100%;font-family:var(--body-font)}
.post-body .contact-form-widget .cf-s{font-size:15px}
.post-body .contact-form-name.cf-s{width:calc(50% - 5px)}
.rtl .post-body .contact-form-name{float:right}
.post-body .contact-form-email.cf-s{float:right;width:calc(50% - 5px)}
.rtl .post-body .contact-form-email{float:left}
.post-body .contact-form-button-submit{font-size:15px}
.post-body pre,pre.code-box{display:block;background-color:var(--gray-bg);font-family:Monospace;font-size:13px;color:var(--title-color);white-space:pre-wrap;line-height:1.4em;padding:20px;border:1px solid var(--border-color);border-radius:var(--radius)}
.post-body .google-auto-placed{margin:25px 0}
.youtube-video{position:relative;width:100%;padding:0;padding-top:56%}
.youtube-video iframe{position:absolute;top:0;left:0;width:100%;height:100%}
.entry-labels{display:flex;flex-wrap:wrap;margin:20px 0 0}
.entry-labels > *{display:flex;align-items:center;height:20px;background-color:var(--gray-bg);font-size:12px;color:var(--title-color);padding:0 6px;margin:5px 5px 0 0}
.rtl .entry-labels > *{margin:5px 0 0 5px}
.entry-labels span{background-color:var(--title-color);color:var(--widget-bg)}
.is-dark .entry-labels span{background-color:var(--outer-bg);color:var(--title-color)}
.entry-labels a:hover{color:var(--title-hover-color)}
.post-share{padding:15px 20px 20px;border-top:1px solid var(--border-color)}
ul.share-a{display:flex;flex-wrap:wrap;align-items:flex-start}
.share-a .btn{display:flex;align-items:center;justify-content:center;width:36px;height:36px;font-size:16px;color:#fff;font-weight:400;overflow:hidden;margin:5px 5px 0 0}
.rtl .share-a .btn{margin:5px 0 0 5px}
.share-a .email .btn{font-size:18px}
.share-a .has-span .btn{width:auto;justify-content:space-between;padding:4px}
.share-a .has-span .btn:before{display:flex;align-items:center;justify-content:center;flex-shrink:0;width:28px;height:28px;background-color:rgba(255,255,255,0.08);border-radius:var(--radius)}
.share-a .btn span{font-size:14px;padding:0 15px}
.share-a .sl-btn{position:relative;overflow:visible;font-size:18px;color:var(--title-color);margin:5px 10px 0 0;border:1px solid var(--border-color);border-radius:var(--radius)}
.share-a .sl-btn:before,.share-a .sl-btn:after{position:absolute;content:'';height:0;width:0;pointer-events:none;top:calc(50% - 6px);right:-12px;border:6px solid transparent;border-left-color:var(--border-color);transition:all .17s ease}
.share-a .sl-btn:after{top:calc(50% - 5px);right:-10px;border:5px solid transparent;border-left-color:var(--widget-bg)}
.sl-btn .sl-ico:before{display:block;content:'\e80d';font-family:'Material Icons Round';font-style:normal;line-height:0;font-weight:400}
.rtl .share-a .sl-btn{margin:5px 0 0 10px;transform:rotate3d(0,1,0,180deg)}
.share-a .show-more .btn{background-color:rgba(155,155,155,0.15);font-size:28px;color:rgba(155,155,155,0.9)}
.share-a .show-more .btn:before{content:'\e145';font-family:'Material Icons Round';font-weight:400}
.share-a li .btn:not(.sl-btn):hover{opacity:.9}
.share-modal{display:flex;flex-direction:column;align-items:center;position:fixed;top:50%;left:50%;width:440px;max-width:calc(100% - 40px);z-index:1010;transform:translate(-50%,0);visibility:hidden;opacity:0;transition:all .17s ease}
.modal-inner{display:flex;flex-direction:column;width:100%;background-color:var(--widget-bg);overflow:hidden;border-radius:var(--radius);box-shadow:0 1px 2px rgba(0,0,0,0.05),0 5px 15px 0 rgba(0,0,0,0.15)}
.modal-header{display:flex;align-items:center;position:relative;overflow:hidden;padding:20px;box-shadow:0 1px 8px rgba(0,0,0,0.1)}
.is-dark .modal-header{box-shadow:0 1px 8px rgba(0,0,0,0.15)}
.modal-thumb{width:70px;height:50px;margin:0 12px 0 0}
.rtl .modal-thumb{margin:0 0 0 12px}
.modal-title{display:-webkit-box;flex:1;width:100%;font-size:15px;color:var(--title-color);line-height:1.3em;overflow:hidden;-webkit-line-clamp:2;-webkit-box-orient:vertical}
.modal-title .strong{font-weight:700;margin:0 6px 0 0}
.rtl .modal-title .strong{margin:0 0 0 6px}
.modal-title .title{opacity:.8}
ul.share-b{display:grid;grid-template-columns:repeat(3,1fr);grid-gap:10px;position:relative;padding:20px}
.share-b a{display:flex;align-items:center;justify-content:flex-start;height:34px;font-size:14px;color:#fff;padding:4px}
.share-b a:before{display:flex;align-items:center;justify-content:center;background-color:rgba(255,255,255,0.08);width:26px;height:26px;margin:0 6px 0 0;border-radius:var(--radius)}
.share-b .email a:before{font-size:16px}
.rtl .share-b a:before{margin:0 0 0 6px}
.share-b a:hover{opacity:.9}
.hide-modal{display:flex;align-items:center;justify-content:center;width:50px;height:50px;color:#fff;background-color:rgba(22,22,26,0.5);font-size:24px;margin:40px 0 0;border-radius:40px;transform:rotate(45deg);transition:all .25s ease;transition-delay:.1s;transition-property:transform}
.hide-modal:before{content:'\e5cd';font-family:'Material Icons Round';font-weight:400}
.share-active .share-modal{transform:translate(-50%,-50%);visibility:visible;opacity:1}
.share-active .hide-modal{transform:rotate(0deg)}
#share-overlay{background-color:rgba(22,22,26,0.8)}
.is-dark #share-overlay{rgba(22,22,26,0.92)}
.share-active #share-overlay{visibility:visible;opacity:1}
.post-widget{margin:25px 0 0}
.about-author{display:flex;background-color:var(--widget-bg);padding:20px;border-radius:var(--radius);box-shadow:var(--widget-shadow)}
.about-author .author-avatar{width:60px;height:60px;margin:0 15px 0 0;border-radius:50%;box-shadow:var(--avatar-shadow)}
.rtl .about-author .author-avatar{margin:0 0 0 15px}
.about-author .author-title{font-size:18px;color:var(--title-color);font-weight:var(--title-weight);margin:0 0 10px}
.about-author .author-title a{color:var(--title-color)}
.about-author .author-title a:hover{color:var(--title-hover-color)}
.author-description{flex:1}
.author-description .author-text{display:block;font-size:14px;font-weight:400}
.author-description .author-text br,.author-description .author-text a{display:none}
ul.author-links{display:flex;flex-wrap:wrap;padding:0}
.author-links li{margin:10px 12px 0 0}
.rtl .author-links li{margin:10px 0 0 12px}
.author-links li a{display:block;font-size:14px;color:var(--text-color);padding:0}
.author-links li.email a,.author-links li.external-link a{font-size:16px}
.rtl .author-links li.external-link a{transform:rotate3d(0,1,0,180deg)}
.author-links li a:hover{opacity:.9}
#buzzspot-pro-related-posts{display:none}
#related-wrap{background-color:var(--widget-bg);padding:20px;border-radius:var(--radius);box-shadow:var(--widget-shadow)}
.related-content .loader{height:180px}
.related-items{display:grid;grid-template-columns:repeat(3,1fr);grid-gap:20px}
.related-items .post{display:flex;flex-direction:column}
.related-items .entry-thumbnail{width:100%;height:140px;margin:0 0 10px}
.related-items .entry-title{font-size:15px}
.related-items .entry-meta{margin:5px 0 0}
.buzzspot-pro-blog-post-comments{display:none;flex-direction:column;background-color:var(--widget-bg);padding:20px;border-radius:var(--radius);box-shadow:var(--widget-shadow)}
.buzzspot-pro-blog-post-comments.is-visible{display:flex}
.buzzspot-pro-blog-post-comments:not(.comments-system-blogger){padding:10px 20px}
.buzzspot-pro-blog-post-comments .fb_iframe_widget_fluid_desktop{float:left;display:block!important;width:calc(100% + 16px)!important;max-width:calc(100% + 16px)!important;margin:0 -8px}
.buzzspot-pro-blog-post-comments .fb_iframe_widget_fluid_desktop span,.buzzspot-pro-blog-post-comments .fb_iframe_widget_fluid_desktop iframe{float:left;display:block!important;width:100%!important}
#disqus_thread,.fb-comments{clear:both;padding:0}
#comments h4#comment-post-message{display:none;float:none}
.comments-title{margin:0}
.has-comments .comments-title.no-message{margin:0 0 5px}
.comments .comment-content{display:block;font-family:var(--text-font);font-size:14px;color:var(--text-color);line-height:1.5em;margin:10px 0 0}
.comments .comment-content > a:hover{text-decoration:underline}
.comment-thread .comment{position:relative;list-style:none;padding:20px 0 0;margin:20px 0 0;border-top:1px solid var(--border-color)}
.comment-thread .comment .comment{background-color:var(--gray-bg);padding:20px;border:0;border-radius:var(--radius)}
.comment-thread ol{padding:0;margin:0}
.comment-thread .comment-replies ol{padding:0 0 4px}
.toplevel-thread ol > li:first-child{margin:0;border:0}
.toplevel-thread ol > li:first-child > .comment-block{padding-top:0;margin:0;border:0}
.comment-thread ol ol .comment:before{position:absolute;content:'\f060';left:-30px;top:-5px;font-family:'Material Icons Round';font-size:20px;color:var(--border-color);font-weight:400}
.rtl .comment-thread ol ol .comment:before{left:unset;right:-30px;transform:rotate(-180deg)}
.comments .comment-replybox-single iframe{padding:0 0 0 48px;margin:10px 0 -5px}
.rtl .comments .comment-replybox-single iframe{padding:0 48px 0 0}
.comment-thread .avatar-image-container{position:absolute;top:20px;left:0;width:35px;height:35px;overflow:hidden;border-radius:50%;box-shadow:var(--avatar-shadow)}
.rtl .comment-thread .avatar-image-container{left:auto;right:0}
.comment-thread .comment .comment .avatar-image-container{left:20px}
.rtl .comment-thread .comment .comment .avatar-image-container{left:unset;right:20px}
.avatar-image-container img{display:block;width:100%;height:100%}
.comments .comment-header{padding:0 0 0 48px}
.rtl .comments .comment-header{padding:0 48px 0 0}
.comments .comment-header .user{display:inline-block;font-family:var(--title-font);font-size:16px;color:var(--title-color);font-weight:var(--title-weight);font-style:normal}
.comments .comment-header .user a{color:var(--title-color)}
.comments .comment-header .user a:hover{color:var(--title-hover-color)}
.comments .comment-header .icon.user{display:none}
.comments .comment-header .icon.blog-author{display:inline-block;font-size:14px;color:var(--main-color);vertical-align:top;margin:-5px 0 0 4px}
.rtl .comments .comment-header .icon.blog-author{margin:-5px 4px 0 0}
.comments .comment-header .icon.blog-author:before{content:'\ef76';font-family:'Material Icons Round';font-weight:400}
.comments .comment-header .datetime{display:block;font-size:12px;font-weight:var(--light-weight);margin:1px 0 0}
.comment-header .datetime a{color:var(--meta-color)}
.comments .comment-actions{display:block;margin:0}
.comments .comment-actions a{display:inline-block;font-size:14px;color:var(--main-color);font-weight:400;font-style:normal;margin:10px 15px 0 0}
.rtl .comments .comment-actions a{margin:10px 0 0 15px}
.comments .comment-actions a:hover{color:var(--main-color);text-decoration:underline}
.item-control{display:none}
.loadmore.loaded a{display:inline-block;border-bottom:1px solid rgba(155,155,155,.51);text-decoration:none;margin-top:15px}
.comments .continue{display:none}
.comments .comment-replies{padding:0 0 0 48px}
.rtl .comments .comment-replies{padding:0 48px 0 0}
.thread-expanded .thread-count a,.loadmore.hidden{display:none}
.comments .footer{float:left;width:100%;font-size:13px;margin:0}
p.comments-message{font-size:14px;color:var(--meta-color);font-style:italic;padding:0 0 15px;margin:15px 0 0;border-bottom:1px solid var(--border-color)}
p.comments-message.no-new-comments{padding:0;border:0}
p.comments-message > a{color:var(--main-color)}
p.comments-message > a:hover{color:var(--title-color)}
p.comments-message > em{color:#ff3f34;font-style:normal;margin:0 3px}
#comments[data-embed='false'] p.comments-message > i{color:var(--main-color);font-style:normal}
.comment-form > p{display:none}
.comments #top-ce.comment-replybox-thread,.no-comments .comment-form{padding:15px 0 0;margin:20px 0 -5px;border-top:1px solid var(--border-color)}
.no-comments .comment-form{margin-top:0;border:0}
.comments #top-continue a{display:flex;align-items:center;justify-content:center;width:100%;height:34px;font-size:14px;color:var(--title-color);font-weight:500;margin:25px 0 0;border:1px solid var(--border-color);border-radius:var(--radius)}
.comments #top-continue a:hover{color:var(--title-hover-color)}
#custom-ads,#buzzspot-pro-post-footer-ads{position:relative;float:left;width:100%;opacity:0;visibility:hidden}
#custom-ads{padding:0 20px}
#before-ad .widget-title,#after-ad .widget-title{display:block}
#before-ad .widget-title > .title,#after-ad .widget-title > .title{font-size:10px;color:var(--meta-color);font-weight:400;line-height:1;margin:0 0 6px}
#before-ad .widget{position:relative;margin:0 0 20px}
#after-ad .widget{position:relative;margin:20px 0 0}
#buzzspot-pro-new-before-ad #before-ad,#buzzspot-pro-new-after-ad #after-ad{display:block}
#buzzspot-pro-new-before-ad #before-ad .widget,#buzzspot-pro-new-after-ad #after-ad .widget{margin:0}
#post-footer-ads .widget{position:relative}
.post-nav{display:flex;flex-wrap:wrap;justify-content:space-between;font-size:14px;font-weight:var(--light-weight)}
.post-nav > *{display:flex;align-items:center;color:var(--meta-color);margin:0 -4px}
.post-nav a:hover{color:var(--main-color)}
.post-nav span{color:var(--meta-color);cursor:no-drop;opacity:.65}
.post-nav .post-nav-link:before,.post-nav .post-nav-link:after{font-family:'Material Icons Round';font-size:16px;line-height:1;font-weight:400}
.post-nav-newer-link:before,.rtl .post-nav-older-link:after{content:'\e5cb'}
.post-nav-older-link:after,.rtl .post-nav-newer-link:before{content:'\e5cc'}
#blog-pager{display:flex;justify-content:center;margin:25px 0 0}
#blog-pager .load-more{display:flex;align-items:center;justify-content:center;height:34px;background:var(--button-bg);font-size:14px;color:var(--button-color);padding:0 30px}
#blog-pager #buzzspot-pro-load-more-link:after{content:'\e5cf';display:inline-block;font-family:'Material Icons Round';font-size:20px;font-weight:400;margin:-1px 0 0}
#blog-pager #buzzspot-pro-load-more-link:hover{opacity:.9}
#blog-pager .no-more.show{display:flex;background:var(--gray-bg);color:var(--meta-color);cursor:not-allowed;padding:0 20px}
#blog-pager .loading,#blog-pager .no-more{display:none}
#blog-pager .loading .loader{height:34px}
#blog-pager .loader:after{width:28px;height:28px}
.sidebar{position:relative;float:left;width:100%;display:grid;grid-template-columns:100%;grid-gap:25px}
.sidebar > .widget{display:flex;flex-direction:column;width:100%;background-color:var(--widget-bg);padding:20px;border-radius:var(--radius);box-shadow:var(--widget-shadow)}
.sidebar .widget.is-ad{background-color:transparent;padding:0;border-radius:0;box-shadow:none}
.sidebar .title-wrap{display:flex;margin:0 0 20px}
.sidebar .title-wrap > .title{position:relative;font-size:17px;color:var(--title-color);line-height:1;margin:0}
.sidebar .widget.is-ad > .widget-title{display:none}
.sidebar ul.social-icons{display:grid;grid-template-columns:repeat(4,1fr);grid-gap:6px}
.sidebar .social-icons li{display:flex}
.sidebar .social-icons a{display:flex;flex-direction:column;align-items:center;justify-content:center;width:100%;font-size:18px;color:#fff;font-weight:400;overflow:hidden;padding:6px}
.sidebar .social-icons .rss a,.sidebar .social-icons .email a,.sidebar .social-icons .external-link a{font-size:20px}
.sidebar .social-icons a:before{display:flex;align-items:center;justify-content:center;width:100%;height:34px;background-color:rgba(255,255,255,0.08);border-radius:var(--radius)}
.sidebar .social-icons span{display:-webkit-box;font-size:14px;overflow:hidden;-webkit-line-clamp:1;-webkit-box-orient:vertical;padding:5px 0 0}
.sidebar .social-icons a:hover{opacity:.9}
.pbt-section .loader{height:180px}
.side-items{display:grid;grid-template-columns:repeat(2,1fr);grid-gap:20px}
.side-items .post{display:flex;flex-direction:column}
.side-items .entry-thumbnail{width:100%;height:90px;margin:0 0 10px}
.side-items .entry-index{display:flex;align-items:center;justify-content:center;position:absolute;left:12px;bottom:12px;width:18px;height:18px;background:var(--thumbtag-bg);font-size:10px;color:var(--thumbtag-color);font-weight:500;text-transform:uppercase;line-height:0;z-index:2;border-radius:var(--radius)}
.rtl .side-items .entry-index{left:unset;right:12px}
.side-items .entry-title{font-size:14px}
.cmm1-items{display:grid;grid-template-columns:1fr;grid-gap:25px}
.cmm1-items .entry-inner{display:flex;align-items:center}
.cmm1-items .entry-thumbnail{width:45px;height:45px;z-index:1;margin:0 13px 0 0;border-radius:50%;box-shadow:var(--avatar-shadow)}
.rtl .cmm1-items .entry-thumbnail{margin:0 0 0 13px}
.cmm1-items .entry-header{flex:1}
.cmm1-items .entry-title{font-size:14px}
.cmm1-items .entry-inner:hover .entry-title{color:var(--title-hover-color)}
.cmm1-items .cmm-snippet{font-size:12px;color:var(--text-color);line-height:1.3em;margin:4px 0 0}
.FeaturedPost .post{display:flex;flex-direction:column}
.FeaturedPost .post .entry-thumbnail{width:100%;height:160px;margin:0 0 12px}
.FeaturedPost .post .entry-title{font-size:19px}
.FeaturedPost .post .entry-meta{flex-wrap:wrap;margin:6px 0 0}
.list-style li{font-size:14px}
.list-style li a,.text-list li{display:block;color:var(--title-color);padding:8px 0}
.list-style li a.has-count{display:flex;justify-content:space-between}
.list-style li:first-child a,.text-list li:first-child{padding:0 0 8px}
.list-style li:last-child a,.text-list li:last-child{padding:8px 0 0}
.list-style li a:hover{color:var(--title-hover-color)}
.list-style .count-style{display:inline-block;color:var(--meta-color)}
.cloud-label ul{display:flex;flex-wrap:wrap;margin:-6px 0 0}
.cloud-label li{margin:6px 5px 0 0}
.rtl .cloud-label li{margin:6px 0 0 5px}
.cloud-label li a{display:flex;height:28px;background-color:var(--gray-bg);color:var(--title-color);font-size:14px;font-weight:400;align-items:center;padding:0 12px}
.cloud-label li a:hover{color:var(--title-hover-color)}
.cloud-label .label-count{display:inline-block;margin:0 0 0 6px}
.rtl .cloud-label .label-count{margin:0 6px 0 0}
.BlogSearch .search-form{display:flex;height:36px;overflow:hidden;padding:2px;border:1px solid var(--border-color);border-radius:var(--radius)}
.is-dark .BlogSearch .search-form{background-color:var(--gray-bg)}
.BlogSearch .search-input{width:100%;flex:1;font-size:14px;color:var(--text-color);padding:0 8px}
.BlogSearch .search-input::placeholder{color:var(--text-color);opacity:.65}
.BlogSearch .search-action{background:var(--button-bg);font-size:14px;color:var(--button-color);cursor:pointer;padding:0 13px}
.BlogSearch .search-action:hover{opacity:.9}
.MailChimp.widget{border-top:5px solid var(--button-border)}
.MailChimp .mailchimp-header{display:flex;flex-direction:column;align-items:center;text-align:center}
.MailChimp .mailchimp-header:before{display:flex;align-items:center;justify-content:center;align-self:center;content:'\e0e1';font-family:'Material Icons Round';width:34px;height:34px;background:var(--button-bg);font-size:20px;color:var(--button-color);font-weight:400;line-height:1;margin:0 0 20px;border-radius:50%}
.is-dark .MailChimp .mailchimp-header:before{color:var(--title-color)}
.MailChimp .mailchimp-title{font-size:21px;color:var(--title-color);font-weight:var(--title-weight);margin:0 0 10px}
.MailChimp .mailchimp-text{font-size:14px;color:var(--text-color);margin:0 0 15px}
.MailChimp .mailchimp-email-address{width:100%;height:34px;font-size:14px;color:var(--text-color);text-align:center;padding:0 10px;margin:0 0 10px;border:1px solid var(--border-color);border-radius:var(--radius)}
.is-dark .MailChimp .mailchimp-email-address{background-color:var(--gray-bg)}
.MailChimp .mailchimp-email-address::placeholder{color:var(--text-color);opacity:.65}
.MailChimp .mailchimp-email-address:focus{border-color:var(--button-border)}
.MailChimp .mailchimp-submit{width:100%;height:34px;background:var(--button-bg);font-size:14px;color:var(--button-color);font-weight:400;cursor:pointer;padding:0 20px}
.MailChimp .mailchimp-submit:hover{opacity:.9}
.Profile ul li{float:left;width:100%;padding:20px 0 0;margin:20px 0 0;border-top:1px solid var(--border-color)}
.Profile ul li:first-child{padding:0;margin:0;border:0}
.Profile .individual,.Profile .team-member{display:flex;align-items:center}
.Profile .profile-img{width:45px;height:45px;background-color:var(--gray-bg);overflow:hidden;color:transparent!important;margin:0 13px 0 0;border-radius:50%;box-shadow:var(--avatar-shadow)}
.rtl .Profile .profile-img{margin:0 0 0 13px}
.Profile .profile-info{flex:1}
.Profile .profile-name{display:block;font-family:var(--title-font);font-size:15px;color:var(--title-color);font-weight:var(--title-weight)}
.Profile .profile-name:hover{color:var(--title-hover-color)}
.Profile .profile-link{display:block;font-size:12px;color:var(--meta-color)}
.Profile .profile-link:hover{color:var(--main-color)}
.Text .widget-content{font-family:var(--text-font);font-size:14px;color:var(--text-color)}
.Image .image-caption{font-family:var(--text-font);font-size:14px;margin:6px 0 0}
.contact-form-widget .cf-s{float:left;width:100%;height:34px;font-size:14px;color:var(--text-color);padding:0 10px;margin:0 0 10px;border:1px solid var(--border-color);border-radius:var(--radius)}
.is-dark .contact-form-widget .cf-s{background-color:var(--gray-bg)}
.contact-form-email-message.cf-s{float:left;width:100%;height:auto;resize:vertical;padding:10px}
.contact-form-widget .cf-s::placeholder{color:var(--text-color);opacity:.9}
.contact-form-widget .cf-s:focus{border-color:var(--button-border)}
.contact-form-button-submit{float:left;width:100%;height:34px;background:var(--button-bg);font-family:inherit;font-size:14px;color:var(--button-color);font-weight:400;cursor:pointer;padding:0 20px;border:0;border-radius:var(--radius)}
.contact-form-button-submit:hover{opacity:.9}
.contact-form-widget p{margin:0}
.contact-form-widget .contact-form-error-message-with-border,.contact-form-widget .contact-form-success-message-with-border{float:left;width:100%;background-color:rgba(0,0,0,0);font-size:13px;color:#e74c3c;text-align:left;line-height:1;margin:10px 0 0;border:0}
.contact-form-widget .contact-form-success-message-with-border{color:#27ae60}
.rtl .contact-form-error-message-with-border,.rtl .contact-form-success-message-with-border{text-align:right}
.contact-form-cross{cursor:pointer;margin:0 0 0 3px}
.rtl .contact-form-cross{margin:0 3px 0 0}
.Attribution a{display:flex;align-items:center;font-size:14px;color:var(--title-color);font-weight:var(--title-weight)}
.Attribution a > svg{width:16px;height:16px;fill:var(--main-color);margin:0 4px 0 0}
.rtl .Attribution a > svg{margin:0 0 0 4px}
.Attribution a:hover{color:var(--title-hover-color)}
.Attribution .copyright{font-size:12px;color:var(--meta-color);padding:0 20px;margin:2px 0 0}
#google_translate_element{position:relative;overflow:hidden}
.Stats .text-counter-wrapper{display:flex;align-items:center;font-size:18px;color:var(--meta-color);font-weight:700;text-transform:uppercase;line-height:1;margin:0}
.Stats .text-counter-wrapper:before{content:'\e202';font-family:'Material Icons Round';font-size:22px;color:var(--title-color);font-weight:400;margin:0 4px 0 0}
.rtl .Stats .text-counter-wrapper:before{margin:0 0 0 4px}
.ReportAbuse > h3{display:flex;font-size:14px;font-weight:400}
.ReportAbuse > h3:before{content:'\e002';font-family:'Material Icons Round';font-size:18px;color:var(--main-color);margin:0 3px 0 0}
.rtl .ReportAbuse > h3:before{margin:0 0 0 3px}
.ReportAbuse > h3 a:hover{text-decoration:underline}
#footer-ads-wrap{position:relative;float:left;width:100%;background-color:var(--footerad-bg);margin:0;box-shadow:var(--widget-shadow)}
#footer-ads-wrap .widget{padding:20px 0}
#footer-ads-wrap.has-border,.is-dark #footer-ads-wrap{border-bottom:1px solid var(--footerad-border)}
#footer-wrapper{position:relative;float:left;width:100%;background-color:var(--footer-bg);box-shadow:var(--widget-shadow)}
.primary-footer{--title-color:var(--footer-color);--text-color:var(--footer-text-color)}
#buzzspot-pro-about-section{flex-wrap:wrap;padding:40px 0}
.about-section .Image{display:flex;justify-content:space-between;align-items:center;width:calc(100% - $(sidebar.width + 30px))}
.footer-info{flex:1}
.footer-info .title{font-size:15px;color:var(--title-color);text-transform:uppercase;margin:0 0 10px}
.footer-logo{padding:0 30px 0 0}
.rtl .footer-logo{padding:0 0 0 30px}
.footer-logo img{display:block;width:auto;height:auto;max-height:40px}
.footer-info .image-caption{font-size:14px;color:var(--text-color);margin:0}
.footer-info .image-caption a{color:var(--title-color)}
.footer-info .image-caption a:hover{opacity:.9}
.about-section .LinkList{width:$(sidebar.width);display:flex;align-items:center;justify-content:flex-end;margin:0}
.about-section ul.social-icons{display:flex;flex-wrap:wrap}
.about-section .social-icons li{margin:0 0 0 10px}
.rtl .about-section .social-icons li{margin:0 10px 0 0}
.about-section .social-icons a{display:flex;width:34px;height:34px;background-color:var(--gray-bg);font-size:16px;color:var(--title-color);align-items:center;justify-content:center}
.about-section .social-icons .rss a,.about-section .social-icons .email a,.about-section .social-icons .external-link a{font-size:20px}
.about-section .social-icons a:hover{color:#fff}
.footer-bar{background-color:var(--footerbar-bg);color:var(--footerbar-color);padding:20px 0}
.footer-bar.has-border{border-top:1px solid var(--footerbar-border-color)}
.footer-bar .footer-copyright{font-size:14px;font-weight:400;margin:0}
.footer-bar .footer-copyright a{color:var(--footerbar-color)}
.footer-bar .footer-copyright a:hover{color:var(--footerbar-hover-color)}
#footer-menu{position:relative;display:block;margin:0}
.footer-menu ul{display:flex;flex-wrap:wrap}
.footer-menu ul li a{font-size:14px;color:var(--footerbar-color);padding:0;margin:0 0 0 25px}
.rtl .footer-menu ul li a{margin:0 25px 0 0}
#footer-menu ul li a:hover{color:var(--footerbar-hover-color)}
.is-error #main-wrapper{width:100%}
.is-error #sidebar-wrapper{display:none}
.errorWrap{color:var(--title-color);text-align:center;padding:60px 0}
.errorWrap h3{font-size:160px;color:var(--title-color);line-height:1;margin:0 0 25px}
.errorWrap h4{font-size:27px;color:var(--title-color);margin:0 0 25px}
.errorWrap p{color:var(--text-color);font-size:15px;margin:0 0 15px}
.errorWrap a{display:inline-block;height:34px;background:var(--button-bg);font-size:14px;color:var(--button-color);font-weight:400;line-height:34px;padding:0 30px;margin:15px 0 0}
.errorWrap a:hover{opacity:.9}
.cookie-choices-info{display:none;visibility:hidden;opacity:0}
.cookie-consent{display:none;position:fixed;bottom:20px;left:20px;width:300px;background-color:var(--cookie-bg);z-index:1020;padding:20px;visibility:hidden;opacity:0;border-radius:var(--radius);box-shadow:0 0 10px rgba(0,0,0,0.1);transition:visibility .35s ease,opacity .35s ease,transform .35s ease}
.rtl .cookie-consent{left:unset;right:20px}
.cookie-consent.is-visible{visibility:visible;opacity:1}
.consent-text{font-size:14px;color:var(--cookie-color);margin:0 0 15px}
.consent-text a{color:var(--main-color);text-decoration:underline}
.consent-text a:after{display:inline-block;content:'\e89e';font-family:'Material Icons Round';font-weight:400;vertical-align:middle;margin:0 0 0 3px}
.rtl .consent-text a:after{margin:0 3px 0 0}
.consent-text a:hover{opacity:.9}
.consent-button{display:inline-block;height:34px;background:var(--button-bg);font-size:14px;color:var(--button-color);font-weight:400;line-height:34px;padding:0 20px}
.consent-button:hover{opacity:.9}
#back-top{display:flex;align-items:center;justify-content:center;position:fixed;bottom:20px;right:20px;width:34px;height:34px;background:var(--button-bg);font-size:24px;color:var(--button-color);z-index:50;opacity:0;visibility:hidden;transition:visibility .17s ease,opacity .17s ease}
.rtl #back-top{right:auto;left:20px}
#back-top:before{content:'\e5ce';font-family:'Material Icons Round';font-weight:400}
#back-top.show{opacity:1;visibility:visible}
#back-top:hover{opacity:.9}
ins.adsbygoogle-noablate[data-anchor-shown="true"]{z-index:990!important}
#content-wrapper > .google-auto-placed,#content-wrapper .container > .google-auto-placed{display:none!important}
#hidden-widgets{display:none;visibility:hidden}
.CSS_LIGHTBOX{z-index:999999!important}
.CSS_LIGHTBOX_BG_MASK{background-color:rgba(0,0,0,0.9)!important;opacity:1!important;backdrop-filter:blur(1px)}
.CSS_LIGHTBOX_BTN_CLOSE{background:transparent!important;top:10px!important;right:15px!important}
.CSS_LIGHTBOX_BTN_CLOSE:before{content:'\e5cd';font-family:'Material Icons Round';color:#fff;font-size:24px;font-weight:400}
.CSS_LIGHTBOX_BTN_CLOSE:hover:before{opacity:.85}
.rtl .CSS_LIGHTBOX_BTN_CLOSE{right:unset!important;left:15px}
.CSS_LIGHTBOX_ATTRIBUTION_INDEX_CONTAINER .CSS_HCONT_CHILDREN_HOLDER > .CSS_LAYOUT_COMPONENT.CSS_HCONT_CHILD:first-child > .CSS_LAYOUT_COMPONENT{opacity:0}
@media only screen and (max-width: $(row.width + 50px)) {
#outer-wrapper,.is-boxed #outer-wrapper,.is-boxed .header-header{width:100%;max-width:100%;margin:0}
.row-x1{width:100%}
#top-ads-wrap .container,.main-header .container,#ticker-wrapper .container,#trending-wrapper .container,#content-wrapper .container,#footer-ads-wrap .container,#footer-wrapper .container{padding:0 20px}
#main-wrapper{width:calc(70% - 25px)}
#sidebar-wrapper{width:30%}
}
@media only screen and (max-width: 980px) {
.main-header .container{padding:0}
.header-items{flex-wrap:nowrap;--search-width:100%!important}
.mobile-menu-toggle{display:flex}
#buzzspot-pro-main-menu{display:none}
#slide-menu{display:block}
.overlay{-webkit-backdrop-filter:saturate(100%) blur(2px);-ms-backdrop-filter:saturate(100%) blur(2px);-o-backdrop-filter:saturate(100%) blur(2px);backdrop-filter:saturate(100%) blur(2px)}
.nav-active #overlay{visibility:visible;opacity:1}
.flex-left{overflow:hidden;transition:all .17s ease}
.main-logo{flex-shrink:1}
.flex-right{padding:0 0 0 10px}
.rtl .flex-right{padding:0 10px 0 0}
.flex-right,.rtl .flex-right{position:relative;top:unset;left:unset;right:unset}
.darkmode-toggle{width:auto;font-size:18px}
.search-toggle{width:auto;background-color:transparent;font-size:26px;padding:0 16px 0 11px}
.rtl .search-toggle{padding:0 11px 0 16px}
#main-search-wrap{background:var(--header-bg);padding:0 0 0 20px}
.rtl #main-search-wrap{padding:0 20px 0 0}
.search-active .flex-left{visibility:hidden;opacity:0}
}
@media only screen and (max-width: 880px) {
.sz-1.is-ytimg:after{transform:translate(50%,-50%) scale(1)}
.sz-3.is-ytimg:after{transform:translate(50%,-50%) scale(.9)}
#content-wrapper > .container,.is-left #content-wrapper > .container{flex-direction:column!important;justify-content:flex-start}
#main-wrapper,#sidebar-wrapper{width:100%}
#sidebar-wrapper{margin:25px 0 0}
.trending-items{grid-template-columns:repeat(2,1fr)}
.list-items,.grid-items{grid-template-columns:repeat(2,1fr);grid-gap:25px}
.list-items .post{flex-direction:column}
.list-items .entry-thumbnail,.grid-items .entry-thumbnail{width:100%;max-width:100%;height:200px;min-height:auto;margin:0!important}
.list-items .entry-header{flex:unset;align-self:unset;padding:20px}
.list-items .entry-excerpt{display:-webkit-box;overflow:hidden;-webkit-line-clamp:2;-webkit-box-orient:vertical;margin:8px 0 0}
.list-items .entry-meta,.grid-items .entry-meta{font-size:13px;margin:8px 0 0}
.related-items{grid-template-columns:repeat(2,1fr)}
.related-items .entry-thumbnail{height:160px}
.related-items .entry-title{font-size:17px}
.side-items{grid-template-columns:repeat(4,1fr)}
#buzzspot-pro-about-section{flex-wrap:wrap;flex-direction:column}
.about-section .Image{width:100%;flex-direction:column;justify-content:center;text-align:center}
.footer-info{text-align:center;margin:25px 0 0}
.footer-info .title{display:none}
.footer-logo{padding:0!important}
.about-section .LinkList{width:100%;justify-content:center;margin:20px 0 0}
.about-section ul.social-icons{justify-content:center}
.about-section .social-icons li{margin:10px 5px 0!important}
.footer-bar{height:auto;line-height:inherit;padding:25px 0}
.footer-bar .container{flex-direction:column-reverse;justify-content:center}
.footer-bar .footer-copyright,#footer-menu{width:100%;text-align:center}
#footer-menu{padding:0 0 15px}
.footer-menu ul{justify-content:center}
.footer-menu ul li a{display:block;margin:5px 10px 0!important}
.nav-active #back-top{opacity:0!important}
}
@media only screen and (max-width: 680px) {
.sz-2.is-ytimg:after,.sz-3.is-ytimg:after,.sz-4.is-ytimg:after{transform:translate(50%,-50%) scale(.8)}
#top-ads-wrap .container,#ticker-wrapper .container,#trending-wrapper .container,#content-wrapper .container,#footer-ads-wrap .container{padding:0 15px}
#top-ads-wrap .widget{padding:10px 0}
#trending .widget-content{min-height:180px}
.featured-post .entry-thumbnail{height:200px}
.featured-post .entry-header{padding:18px 20px 20px}
.featured-post .entry-title{font-size:21px}
.featured-post .entry-excerpt{display:-webkit-box;font-size:14px;overflow:hidden;-webkit-line-clamp:2;-webkit-box-orient:vertical;margin:8px 0 0}
.featured-post .entry-meta{font-size:13px;margin:8px 0 0}
.list-items,.grid-items{grid-template-columns:1fr;grid-gap:25px}
.list-items .entry-header,.grid-items .entry-header{padding:18px 20px 20px}
.p-eh .entry-meta{margin:15px 0 0}
.item-post h1.entry-title{font-size:31px}
.post-body table{display:block}
.share-modal{max-width:calc(100% - 30px)}
.author-description .author-text,.comments .comment-content{font-size:$(itempost.content.size)}
.related-items .entry-thumbnail{height:130px}
.related-items .entry-title{font-size:15px}
.related-items .entry-category{left:15px;bottom:15px}
.rtl .related-items .entry-category{left:unset;right:15px}
.side-items{grid-template-columns:repeat(2,1fr);grid-gap:20px}
.side-items .entry-thumbnail{height:130px}
.side-items .entry-index{left:15px;bottom:15px}
.rtl .side-items .entry-index{left:unset;right:15px}
.side-items .entry-title{font-size:15px}
.FeaturedPost .post .entry-meta{margin:8px 0 0}
.FeaturedPost .post .sz-2.is-ytimg:after{transform:translate(50%,-50%) scale(.9)}
.errorWrap{padding:15px 15px 30px}
.errorWrap h3{font-size:130px}
.errorWrap h4{line-height:initial}
.cookie-consent{right:0!important;left:0!important;bottom:0;width:100%;padding:20px;border-radius:0}
}
@media only screen and (max-width: 540px) {
.ticker .widget-title .title{display:none}
.ticker-items .entry-title a{opacity:1}
.trending-items{grid-gap:15px}
.trending-items .entry-thumbnail{height:130px}
.trending-items .entry-category{left:15px;bottom:15px}
.rtl .trending-items .entry-category{left:unset;right:15px}
.trending-items .entry-header{flex:1;justify-content:space-between;padding:13px 15px}
.trending-items .entry-title{font-size:15px}
.trending-items .entry-title a{display:-webkit-box;overflow:hidden;-webkit-line-clamp:3;-webkit-box-orient:vertical}
.trending-items .entry-author,.trending-items .entry-time .sp{display:none}
#breadcrumb{margin:0 0 12px}
.item-post h1.entry-title{font-size:26px}
.p-eh .entry-meta .has-time .entry-avatar{flex-shrink:0;width:40px;height:40px;margin:0 7px 0 0}
.rtl .p-eh .entry-meta .has-time .entry-avatar{margin:0 0 0 7px}
.p-eh .entry-meta .al-items{flex-direction:column;line-height:1;padding:0 15px 0 0}
.rtl .p-eh .entry-meta .al-items{padding:0 0 0 15px}
.p-eh .entry-meta .al-items .by{color:var(--title-color)}
.p-eh .entry-meta .al-items .entry-time{font-size:13px;margin:5px 0 0}
.p-eh .entry-meta .al-items .entry-time .sp{display:none}
.share-a .twitter .btn{width:36px}
.share-a .twitter .btn:before{background-color:transparent}
.share-a .twitter .btn span,.share-a .email{display:none}
.share-b a{height:36px}
.share-b a:before{width:100%;background-color:transparent;font-size:16px;margin:0!important}
.share-b .email a:before{font-size:18px}
.share-b span{display:none}
.related-items .entry-thumbnail{height:110px}
.related-items .entry-title{font-size:14px}
.side-items .entry-thumbnail{height:110px}
.side-items .entry-title{font-size:14px}
}
@media only screen and (max-width: 380px) {
.trending-items .entry-thumbnail{height:95px}
.trending-items .is-ytimg .entry-category{display:none}
.trending-items .entry-title{font-size:14px}
.featured-post .entry-thumbnail{height:170px}
.list-items .entry-thumbnail,.grid-items .entry-thumbnail{height:170px}
.item-post h1.entry-title{font-size:23px}
.pbt-toc-inner{min-width:100%}
.share-a .facebook .btn{width:36px}
.share-a .facebook .btn:before{background-color:transparent}
.share-a .facebook .btn span{display:none}
.share-a .email{display:block}
.related-items .entry-thumbnail{height:95px}
.related-items .is-ytimg .entry-category{display:none}
.side-items .entry-thumbnail{height:95px}
}
@media only screen and (max-width: 340px) {
#slide-menu{width:100%}
.errorWrap h3{font-size:110px}
.errorWrap h4{font-size:27px}
}
]]></b:skin>
</b:if>
<b:if cond='data:view.isLayoutMode'>
<b:template-skin><![CDATA[
html,body#layout #outer-wrapper,body#layout .row{width:auto;padding:0}
body#layout{position:relative;width:auto;max-width:100%;background-color:#fff;padding:95px 5px 0;margin:0 0 0 1px;border-width:1px 0 0;border-color:#eceff1}
body#layout:before{content:'BuzzSpot - v1.1.0';position:absolute;top:0;left:5px;right:5px;height:95px;font-family:Roboto,sans-serif;font-size:23px;color:#263238;line-height:95px;text-align:center}
body#layout div.section{display:block;background-color:#eceff1!important;margin:0 5px 10px!important;padding:16px 16px 18px!important;border:0}
body#layout .no-items.section{display:block}
body#layout .section h4{font-size:14px;color:#263238;text-transform:uppercase;margin:0}
body#layout .section h4:after{text-transform:initial;color:#757575;font-weight:400}
body#layout .add_widget a{color:#4385f5!important}
body#layout .widget-wrap3{overflow:hidden}
body#layout .widget-content{width:auto;max-width:none;max-height:none;margin:0;border:1px solid #e7e7e8;border-left:0}
body#layout .locked-widget .widget-content{border-left:1px solid #4385f5}
body#layout .locked-widget .widget-content:hover{border-left-color:#33a453}
body#layout div.layout-title{color:#757575}
body#layout .widget .widget-content a.editlink{border-radius:2px}
body#layout .visibility .editlink{background:#4385f5 url(https://1.bp.blogspot.com/--z1wepFalfQ/YOObl8avCFI/AAAAAAAAAE8/Z-iC0j0LLpo7u2ZpHvW0hGaHhBOvVYYaQCLcBGAsYHQ/s48/edit.png) no-repeat center!important;background-size:20px!important}
body#layout .visibility .editlink:hover{background-color:#33a453!important}
body#layout .draggable-widget .widget-wrap2{background:#4385f5 url(https://1.bp.blogspot.com/-ciJD7MVmo10/YORQlzt9a1I/AAAAAAAAAFk/L4fK5cgelFoWX9rZvGFKZdr1d_RM9kfjACLcBGAsYHQ/s68/drag.png) no-repeat 4px 50%!important;background-size:4px auto!important}
body#layout .draggable-widget .widget-wrap1:hover .widget-wrap2{background-color:#33a453!important}
body#layout .visibility .layout-widget-state.visible{background-image:url(https://1.bp.blogspot.com/-aPoC3YxQo6g/YOOeDVSsJqI/AAAAAAAAAFM/oyvPLSJVIRQpAu-g0gZL89g5Caq4_4DeQCLcBGAsYHQ/s48/visibility_on.png)!important;background-size:24px!important}
body#layout .visibility .layout-widget-state.not-visible{background-image:url(https://1.bp.blogspot.com/-x_kkTMRQfHs/YOOeMUjTE8I/AAAAAAAAAFQ/RRj6YLBNuMEHwTB_81304fCxy8dl7h46gCLcBGAsYHQ/s48/visibility_off.png)!important;background-size:24px!important;opacity:1}
body#layout div.layout-widget-description{display:none;font-size:11px;line-height:1.2em}
body#layout #theme-options,body#layout #main-menu .widget{display:block!important}
body#layout div.pbt-panel{background-color:rgba(67,133,245,0.15)!important;overflow:hidden!important}
body#layout .pbt-panel .widget{float:left;width:49.5%;margin-right:1%}
body#layout .pbt-panel .widget-content{border-color:#d5e3fc!important}
body#layout .pbt-panel .HTML{margin-right:0}
body#layout .pbt-panel div.layout-widget-description,body#layout .mobile-menu-toggle,body#layout .flex-right,body#layout #main-search-wrap{display:none}
body#layout .flex-left{display:flex}
body#layout .main-logo,body#layout .buzzspot-pro-main-menu{width:50%}
body#layout #content-wrapper{padding:0;margin:0}
body#layout #content-wrapper > .container{display:flex;margin:0}
body#layout #main-wrapper{width:67%;padding:0}
body#layout #sidebar-wrapper{width:33%;padding:0}
body#layout #custom-ads{display:flex}
body#layout #custom-ads .section{width:50%}
body#layout #buzzspot-pro-about-section{overflow:hidden!important}
body#layout #buzzspot-pro-about-section .widget{float:left;width:49.5%;margin-right:1%}
body#layout #buzzspot-pro-about-section .LinkList{margin-right:0}
body#layout .footer-bar .container{display:flex}
body#layout #footer-menu,body#layout #footer-copyright{width:50%}
body#layout .section > h4:after{font-size:12px}
body#layout #custom-ads div.section,body#layout div.top-ads,body#layout div.home-ads,body#layout div.footer-ads,body#layout #buzzspot-pro-post-footer-ads{background-color:#d4ecdb!important}
body#layout #pbt-panel > h4:after{content:' - Default Thumbnail, Date Format, Translate Months and More'}
body#layout #top-ads > h4:after{content:' - HTML, Adsense or Image'}
body#layout #main-logo > h4:after{content:' - Recommended Height (40px)'}
body#layout #buzzspot-pro-main-menu > h4:after{content:' - Menu Links, Sub Links and Mega Menu'}
body#layout #ticker > h4:after{content:' - Popular Posts, Recent or Label'}
body#layout #trending > h4:after{content:' - Popular Posts, Recent or Label'}
body#layout #featured > h4:after{content:' - by Featured Post Gadget'}
body#layout .home-ads > h4:after{content:' - HTML, Adsense or Image'}
body#layout #main > h4:after{content:' - Default Blog Posts, AdSense In-Feed, Comments and More'}
body#layout #buzzspot-pro-main-before-ad > h4:after{content:' - Before Post Content (Post Page)'}
body#layout #buzzspot-pro-main-after-ad > h4:after{content:' - After Post Content (Post Page)'}
body#layout #buzzspot-pro-related-posts > h4:after{content:' - Exclusive Non-Duplicate Post System'}
body#layout #buzzspot-pro-post-footer-ads > h4:after{content:' - After Related Posts (Post Page)'}
body#layout #sidebar > h4:after{content:' - Default Gadgets'}
body#layout #footer-ads > h4:after{content:' - HTML, Adsense or Image'}
body#layout #buzzspot-pro-about-section > h4:after{content:' - Site Logo, Description and Social Icons'}
body#layout #footer-copyright > h4:after{content:' - Custom Credits'}
body#layout #footer-menu > h4:after{content:' - Footer Links'}
body#layout #cookie-consent-section > h4:after{content:' - Native Cookie Consent Plugin'}
body#layout:after{content:'Design by - ProBloggerTemplates.com';display:block;font-family:Roboto,sans-serif;font-size:14px;color:rgba(0,0,0,0.54);line-height:1;text-align:center;visibility:visible;padding:20px 0 30px}
body#layout #hidden-widgets{display:none!important}
]]></b:template-skin>
  
  
  
</b:if>
<b:if cond='data:widgets.AdSense.first or data:blog.adsenseClientId'>
  <!-- Google AdSense -->
  <script async='async' crossorigin='anonymous' src='//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js'/>
</b:if>
<b:if cond='data:blog.analyticsAccountNumber'>
  <!-- Google Analytics -->
  <b:include data='blog' name='google-analytics'/>
</b:if>
<b:defaultmarkups>
  <b:defaultmarkup type='Common'>
    <b:includable id='dark-mode'>
      <b:class cond='data:skin.vars.darkmode == &quot;1px&quot;' name='is-dark dark-logo'/>
    </b:includable>
    <b:includable id='customOpenGraphMetaData'>
      <!-- Open Graph Meta Tags -->
      <meta expr:content='data:blog.localeUnderscoreDelimited' property='og:locale'/>
      <b:if cond='data:view.isHomepage'>
        <meta content='website' property='og:type'/>
        <b:elseif cond='data:view.isSingleItem'/>
        <meta content='article' property='og:type'/>
        <b:elseif cond='data:view.isMultipleItems and not data:view.isHomepage'/>
        <meta content='object' property='og:type'/>
      </b:if>
      <meta expr:content='data:view.title.escaped' property='og:title'/>
      <meta expr:content='data:blog.title.escaped' property='og:site_name'/>
      <meta expr:content='data:view.description.escaped' property='og:description'/>
      <meta expr:content='data:blog.url.canonical' property='og:url'/>
      <b:tag cond='data:view.isMultipleItems and data:widgets.Blog.first.posts[0].featuredImage' expr:content='data:widgets.Blog.first.posts[0].featuredImage resizeImage 1600' name='meta' property='og:image'/>
      <b:tag cond='data:view.featuredImage' expr:content='data:view.featuredImage resizeImage 1600' name='meta' property='og:image'/>
      <!-- Twitter Meta Tags -->
      <meta content='summary_large_image' name='twitter:card'/>
      <meta expr:content='data:view.title.escaped' name='twitter:title'/>
      <meta expr:content='data:view.description.escaped' name='twitter:description'/>
      <meta expr:content='data:blog.url.canonical' name='twitter:domain'/>
      <b:tag cond='data:view.isMultipleItems and data:widgets.Blog.first.posts[0].featuredImage' expr:content='data:widgets.Blog.first.posts[0].featuredImage resizeImage 1600' name='meta' property='twitter:image'/>
      <b:tag cond='data:view.featuredImage' expr:content='data:view.featuredImage resizeImage 1600' name='meta' property='twitter:image'/>
    </b:includable>
    <b:includable id='theme-head'>
      <meta expr:content='&quot;text/html; charset=&quot; + data:blog.encoding' http-equiv='Content-Type'/>
      <meta content='width=device-width, initial-scale=1, minimum-scale=1, user-scalable=yes' name='viewport'/>
      <!-- DNS Prefetch -->
      <link href='//fonts.googleapis.com' rel='dns-prefetch'/>
      <link href='//fonts.gstatic.com' rel='dns-prefetch'/>
      <link href='//dnjs.cloudflare.com' rel='dns-prefetch'/>
      <link href='//1.bp.blogspot.com' rel='dns-prefetch'/>
      <link href='//2.bp.blogspot.com' rel='dns-prefetch'/>
      <link href='//3.bp.blogspot.com' rel='dns-prefetch'/>
      <link href='//4.bp.blogspot.com' rel='dns-prefetch'/>
      <link href='//blogger.googleusercontent.com' rel='dns-prefetch'/>
      <link href='//www.blogger.com' rel='dns-prefetch'/>
      <!-- Site Info -->
      <meta content='blogger' name='generator'/>
      <title><data:view.title.escaped/></title>
      <meta expr:content='data:view.description.escaped' name='description'/>
      <link expr:href='data:view.url.canonical' rel='canonical'/>
      <b:if cond='data:blog.adultContent'>
        <meta content='adult' name='rating'/>
      </b:if>
      <link expr:href='data:blog.blogspotFaviconUrl' rel='icon' type='image/x-icon'/>
      <meta expr:content='data:skin.vars.main_color' name='theme-color'/>
      <b:include name='customOpenGraphMetaData'/>
      <!-- Feed Links -->
      <data:blog.feedLinks/><data:blog.meTag/>
      <b:if cond='data:view.isHomepage'>
        <!-- Schema Markup -->
        <script type='application/ld+json'>{&quot;@context&quot;:&quot;http://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;name&quot;:&quot;<data:view.title.escaped/>&quot;,&quot;url&quot;:&quot;<data:view.url.canonical/>&quot;,&quot;potentialAction&quot;:{&quot;@type&quot;:&quot;SearchAction&quot;,&quot;target&quot;:&quot;<data:view.url.canonical/>search?q={search_term_string}&quot;,&quot;query-input&quot;:&quot;required name=search_term_string&quot;}}</script>
      </b:if>
      <!-- Styles and Scripts -->
      <b:tag href='https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/fontawesome.min.css' name='link' rel='stylesheet'/>
      <b:tag cond='data:blog.languageDirection == &quot;rtl&quot;' href='https://fonts.googleapis.com/css2?family=Cairo:wght@400;500;600;700&amp;display=swap' name='link' rel='stylesheet'/>
    </b:includable>
    <b:includable id='theme-body-class'>
      <b:class cond='data:view.isHomepage' name='is-home'/>
      <b:class cond='data:view.isMultipleItems' name='is-multiple'/>
      <b:class cond='data:view.isSingleItem' name='is-single'/>
      <b:class cond='data:view.isPage' name='is-page'/>
      <b:class cond='data:view.isPost' name='is-post'/>
      <b:class cond='data:view.isError' name='is-multiple is-error'/>
      <b:class cond='data:blog.isMobileRequest' name='is-mobile'/>
      <b:class cond='data:skin.vars.boxed == &quot;1px&quot;' name='is-boxed'/>
      <b:class cond='data:skin.vars.sidebar == &quot;1px&quot;' name='is-left'/>
    </b:includable>
    <b:includable id='theme-custom-lang'>
      <b:switch var='data:message'>
        <b:case value='prevPost'/><b:if cond='data:blog.locale.language == &quot;en&quot;'>Previous Post<b:elseif cond='data:blog.locale.language == &quot;es&quot;'/>Artículo Anterior<b:elseif cond='data:blog.locale.language == &quot;pt&quot;'/>Postagem Anterior<b:else/><data:messages.newer/></b:if>
        <b:case value='nextPost'/><b:if cond='data:blog.locale.language == &quot;en&quot;'>Next Post<b:elseif cond='data:blog.locale.language == &quot;es&quot;'/>Artículo Siguiente<b:elseif cond='data:blog.locale.language == &quot;pt&quot;'/>Próxima Postagem<b:else/><data:messages.older/></b:if>
        <b:case value='loadMorePosts'/><b:if cond='data:blog.locale.language == &quot;en&quot;'>Load More<b:elseif cond='data:blog.locale.language == &quot;es&quot;'/>Carga Más<b:elseif cond='data:blog.locale.language == &quot;pt&quot;'/>Carregar Mais<b:elseif cond='data:blog.locale.language == &quot;ar&quot;'/>تحميل المزيد<b:else/><data:messages.loadMorePosts/></b:if>
      </b:switch>
    </b:includable>
    <b:includable id='widget-title'>
      <b:if cond='data:title == &quot;{ads}&quot;'>
        <b:class name='is-ad'/>
        <b:elseif cond='data:widget.type == &quot;AdSense&quot;'/>
        <b:class name='is-ad'/>
      </b:if>
      <b:if cond='data:widget.type == &quot;HTML&quot; and data:title contains &quot;getMailchimp&quot;'>
        <b:class name='MailChimp'/>
      </b:if>
      <b:if cond='data:widget.sectionId == &quot;ticker&quot;'>
        <div class='widget-title'><b:if cond='data:defaultTitle or data:title'><h3 class='title'><data:title/></h3></b:if></div>
        <b:else/>
        <b:if cond='data:defaultTitle or data:title'>
          <b:if cond='data:title != &quot;{ads}&quot; and not (data:widget.type == &quot;HTML&quot; and data:title contains &quot;getMailchimp&quot;)'>
            <b:if cond='data:widget.sectionId not in [&quot;pbt-panel&quot;,&quot;main-logo&quot;,&quot;buzzspot-pro-main-menu&quot;,&quot;top-ads&quot;,&quot;trending&quot;,&quot;home-ads-1&quot;,&quot;home-ads-2&quot;,&quot;footer-ads&quot;,&quot;buzzspot-pro-post-footer-ads&quot;,&quot;buzzspot-pro-about-section&quot;,&quot;footer-copyright&quot;,&quot;footer-menu&quot;]'>
              <div expr:class='data:widget.sectionId in [&quot;featured&quot;] ? &quot;main-title-wrap widget-title&quot; : (data:widget.sectionId in [&quot;sidebar&quot;] ? &quot;title-wrap widget-title&quot; : &quot;widget-title&quot;)'><h3 class='title'><data:title/></h3></div>
            </b:if>
          </b:if>
        </b:if>
      </b:if>
    </b:includable>
    <b:includable id='pagelist-content'>
      <div class='widget-content'>
        <ul class='link-list list-style'>
          <b:loop values='data:links' var='link'>
            <li><a expr:href='data:link.href'><data:link.title/></a></li>
          </b:loop>
        </ul>
      </div>
    </b:includable>
    <b:includable id='linklist-content'>
      <b:if cond='data:widget.sectionId in [&quot;sidebar&quot;,&quot;buzzspot-pro-about-section&quot;]'>
        <b:tag class='widget-content' cond='data:widget.sectionId not in [&quot;buzzspot-pro-about-section&quot;]' name='div'>
          <b:if cond='data:links any l =&gt; l.name contains &quot;getSocial&quot;'>
            <b:if cond='data:widget.sectionId == &quot;sidebar&quot;'>
              <ul class='social-icons social sb-a'>
                <b:loop values='data:links' var='link'>
                  <b:if cond='!(data:link.name contains &quot;getSocial&quot;)'>
                    <li expr:class='data:link.name'><a data-side='true' expr:alt='data:link.name' expr:class='&quot;fa-&quot; + data:link.name + &quot; btn&quot;' expr:href='data:link.target' expr:title='data:link.name' rel='noopener noreferrer' target='_blank'/></li>
                  </b:if>
                </b:loop>
              </ul>
              <b:else/>
              <ul class='social-icons social sb-h'>
                <b:loop values='data:links' var='link'>
                  <b:if cond='!(data:link.name contains &quot;getSocial&quot;)'>
                    <li expr:class='data:link.name'><a expr:alt='data:link.name' expr:class='&quot;fa-&quot; + data:link.name + &quot; btn&quot;' expr:href='data:link.target' expr:title='data:link.name' rel='noopener noreferrer' target='_blank'/></li>
                  </b:if>
                </b:loop>
              </ul>
            </b:if>
            <b:else/>
            <ul class='link-list list-style'>
              <b:loop values='data:links' var='link'>
                <li><a expr:href='data:link.target'><data:link.name/></a></li>
              </b:loop>
            </ul>
          </b:if>
        </b:tag>
        <b:elseif cond='data:widget.sectionId == &quot;buzzspot-pro-main-menu&quot;'/>
        <ul class='main-nav' id='main-nav'>
          <b:loop index='i' values='data:links' var='link'>
            <li expr:id='&quot;item-&quot; + data:i'><b:if cond='data:link.target contains &quot;getPosts&quot;'><b:class name='has-sub mega-menu'/><a expr:data-shortcode='data:link.target' href='#'><data:link.name/></a><b:else/><a expr:href='data:link.target'><data:link.name/></a></b:if></li>
          </b:loop>
        </ul>
        <b:else/>
        <b:tag class='widget-content' cond='data:widget.sectionId not in [&quot;footer-menu&quot;]' name='div'>
          <ul expr:class='data:widget.sectionId in [&quot;footer-menu&quot;] ? &quot;link-list&quot; : &quot;link-list list-style&quot;'>
            <b:loop values='data:links' var='link'>
              <li><a expr:href='data:link.target'><data:link.name/></a></li>
            </b:loop>
          </ul>
        </b:tag>
      </b:if>
    </b:includable>
    <b:includable id='html-content'>
      <b:if cond='data:widget.sectionId == &quot;pbt-panel&quot;'>
        <b:if cond='data:content != &quot;&quot;'>
          <b:tag name='script' type='text/javascript'>
            <b:with expr:value='data:content' var='option'>
              <b:if cond='data:option.viewAllText'>var viewAllText = &quot;<data:option.viewAllText/>&quot;;</b:if>
              <b:if cond='data:option.dateFormat'>var dateFormat = &quot;<data:option.dateFormat/>&quot;;</b:if>
              <b:if cond='data:option.monthName'>
                var monthNames = [&quot;<data:option.monthName.jan/>&quot;,&quot;<data:option.monthName.feb/>&quot;,&quot;<data:option.monthName.mar/>&quot;,&quot;<data:option.monthName.apr/>&quot;,&quot;<data:option.monthName.may/>&quot;,&quot;<data:option.monthName.jun/>&quot;,&quot;<data:option.monthName.jul/>&quot;,&quot;<data:option.monthName.aug/>&quot;,&quot;<data:option.monthName.sep/>&quot;,&quot;<data:option.monthName.oct/>&quot;,&quot;<data:option.monthName.nov/>&quot;,&quot;<data:option.monthName.dec/>&quot;];
              </b:if>
            </b:with>
          </b:tag>
        </b:if>
      <b:elseif cond='data:widget.sectionId == &quot;buzzspot-pro-related-posts&quot;'/>
        <b:with value='data:title ? &quot;$title={&quot; + data:title + &quot;} &quot; : &quot;&quot;' var='relatedTitle'>
          <b:attr expr:value='data:relatedTitle + (data:content contains &quot;results&quot; ? data:content : &quot;&quot;)' name='data-shortcode'/>
        </b:with>
        <b:else/>
        <b:if cond='data:content contains &quot;getPosts&quot; and data:widget.sectionId in [&quot;ticker&quot;,&quot;trending&quot;]'>
          <b:class name='is-visible'/>
        </b:if>
        <b:include name='widget-title'/>
        <div class='widget-content'>
          <b:if cond='data:content contains &quot;getPosts&quot; and data:widget.sectionId in [&quot;ticker&quot;,&quot;trending&quot;,&quot;sidebar&quot;]'>
            <b:attr expr:value='data:content' name='data-shortcode'/>
            <b:elseif cond='data:title contains &quot;getMailchimp&quot;'/>
            <b:attr expr:value='data:title' name='data-shortcode'/>
            <div class='mailchimp-header'>
              <h3 class='mailchimp-title'><data:messages.subscribe/></h3>
              <p class='mailchimp-text excerpt'><data:messages.getEmailNotifications/></p>
            </div>
            <div class='mailchimp-form'>
              <form expr:action='data:content' expr:onsubmit='&quot;window.open(\&quot;&quot; + data:content + &quot;\&quot;, \&quot;popupwindow\&quot;, \&quot;scrollbars=yes,width=550,height=520\&quot;); return true&quot;' method='post' name='mc-embedded-subscribe-form' novalidate='' target='popupwindow'>
                <input class='mailchimp-email-address' expr:aria-label='data:messages.emailAddress' expr:placeholder='data:messages.emailAddress' name='EMAIL' type='email' value=''/>
                <input class='mailchimp-submit btn' expr:value='data:messages.subscribe' name='subscribe' type='submit'/>
              </form>
            </div>
            <b:else/>
            <data:content/>
          </b:if>
        </div>
      </b:if>
    </b:includable>
    <b:includable id='image-content'>
      <b:if cond='data:widget.sectionId == &quot;pbt-panel&quot;'>
        <b:tag name='script' type='text/javascript'>var noThumbnail = &quot;<b:eval expr='resizeImage(data:sourceUrl, 72, &quot;1:1&quot;)'/>&quot;;</b:tag>
        <b:elseif cond='data:widget.sectionId == &quot;main-logo&quot;'/>
        <a class='logo-img' expr:href='data:blog.homepageUrl.canonical' rel='home'>
          <img expr:alt='data:blog.title' expr:data-src='data:sourceUrl' expr:height='data:height' expr:src='data:sourceUrl' expr:title='data:blog.title' expr:width='data:width'>
            <b:loop values='[&quot;.png&quot;,&quot;.jpg&quot;,&quot;.gif&quot;]' var='imageType'>
              <b:attr cond='data:link and contains(data:link, data:imageType)' expr:value='data:link' name='data-dark-src'/>
            </b:loop>
          </img>
          <b:if cond='data:view.isMultipleItems'><h1 id='h1-off'><data:blog.title/></h1></b:if>
      	</a>
        <b:elseif cond='data:widget.sectionId == &quot;buzzspot-pro-about-section&quot;'/>
        <a class='footer-logo custom-image' expr:href='data:blog.homepageUrl.canonical' rel='home'>
          <img expr:alt='data:blog.title' expr:data-src='data:sourceUrl' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_img&quot;' expr:src='data:sourceUrl' expr:width='data:width'>
            <b:loop values='[&quot;.png&quot;,&quot;.jpg&quot;,&quot;.gif&quot;]' var='imageType'>
              <b:attr cond='data:link and contains(data:link, data:imageType)' expr:value='data:link' name='data-dark-src'/>
            </b:loop>
          </img>
        </a>
        <b:if cond='data:caption'>
          <div class='footer-info'>
            <b:if cond='data:title'><h3 class='title'><data:title/></h3></b:if>
            <b:if cond='data:caption'><p class='image-caption excerpt'><data:caption/></p></b:if>
          </div>
        </b:if>
        <b:else/>
        <div class='widget-content'>
          <div class='custom-image'>
            <b:tag cond='data:link' expr:href='data:link' name='a'>
              <img expr:alt='data:blog.title' expr:id='data:widget.instanceId + &quot;_img&quot;' expr:src='data:sourceUrl'/>
            </b:tag>
          </div>
          <b:if cond='data:caption'>
            <p class='image-caption excerpt'><data:caption/></p>
          </b:if>
        </div>
      </b:if>
    </b:includable>
    <b:includable id='text-content'>
      <b:if cond='data:widget.sectionId == &quot;footer-copyright&quot;'>
        <data:content/>
        <b:elseif cond='data:widget.sectionId == &quot;cookie-consent-section&quot;'/>
        <b:attr expr:value='data:title' name='data-shortcode'/>
        <p class='consent-text excerpt'><data:content/></p>
        <button class='consent-button btn' expr:aria-label='data:messages.ok'><data:messages.ok/></button>
        <b:else/>
        <b:include name='widget-title'/>
        <div class='widget-content excerpt'>
          <data:content/>
        </div>
      </b:if>
    </b:includable>
    <b:includable id='popular-content'>
      <b:if cond='data:widget.sectionId == &quot;ticker&quot;'>
        <div expr:class='&quot;post item-&quot;+data:i'>
          <b:class cond='data:i == 0' name='active'/>
          <h2 class='entry-title'><a expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></a></h2>
        </div>
      <b:elseif cond='data:widget.sectionId == &quot;trending&quot;'/>
        <div expr:class='&quot;post item-&quot;+data:i'>
          <a class='entry-thumbnail' expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><b:if cond='data:post.featuredImage'><span class='thumbnail' expr:data-src='data:post.featuredImage.isYouTube ? resizeImage(data:post.featuredImage.youtubeMaxResDefaultUrl.jsonEscaped, 72, &quot;1:1&quot;) : resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)'/><b:else/><span class='entry-thumbnail' data-src='https://resources.blogblog.com/img/blank.gif'/></b:if><b:class cond='data:post.featuredImage.isYouTube' name='sz-2 is-ytimg'/><b:if cond='data:post.labels and (data:skin.vars.thumbtag == &quot;1px&quot;)'><span class='entry-category'><data:post.labels.first.name/></span></b:if></a>
          <div class='entry-header'>
            <h2 class='entry-title'><a expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></a></h2>
            <b:if cond='data:widgets.Blog.first.allBylineItems.author or data:widgets.Blog.first.allBylineItems.timestamp'><div class='entry-meta'><b:if cond='data:widgets.Blog.first.allBylineItems.author'><span class='entry-author mi'><b:if cond='data:widgets.Blog.first.allBylineItems.author.label'><span class='sp'><data:widgets.Blog.first.allBylineItems.author.label/></span></b:if><span class='author-name'><data:post.author.name/></span></span></b:if><b:if cond='data:widgets.Blog.first.allBylineItems.timestamp'><span class='entry-time mi'><b:if cond='data:widgets.Blog.first.allBylineItems.author and data:widgets.Blog.first.allBylineItems.timestamp.label'><span class='sp'><data:widgets.Blog.first.allBylineItems.timestamp.label/></span></b:if><time class='published' expr:datetime='data:post.date.iso8601'><data:post.date/></time></span></b:if></div></b:if>
          </div>
        </div>
        <b:else/>
        <div expr:class='&quot;post item-&quot;+data:i'>
          <a class='entry-thumbnail' expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><b:if cond='data:post.featuredImage'><span class='thumbnail' expr:data-src='data:post.featuredImage.isYouTube ? resizeImage(data:post.featuredImage.youtubeMaxResDefaultUrl.jsonEscaped, 72, &quot;1:1&quot;) : resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)'/><b:else/><span class='entry-thumbnail' data-src='https://resources.blogblog.com/img/blank.gif'/></b:if><b:class cond='data:post.featuredImage.isYouTube' name='sz-4 is-ytimg'/><span class='entry-index'><b:eval expr='data:i + 1'/></span></a>
          <div class='entry-header'>
            <h2 class='entry-title'><a expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></a></h2>
            <b:if cond='data:widgets.Blog.first.allBylineItems.timestamp'><div class='entry-meta'><span class='entry-time'><time class='published' expr:datetime='data:post.date.iso8601'><data:post.date/></time></span></div></b:if>
          </div>
        </div>
      </b:if>
    </b:includable>
    <b:includable id='featured-content'>
      <div expr:class='data:widget.sectionId == &quot;featured&quot; ? &quot;featured-post&quot; : &quot;post&quot;'>
        <a class='entry-thumbnail' expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><b:if cond='data:post.featuredImage'><span class='thumbnail' expr:data-src='data:post.featuredImage.isYouTube ? resizeImage(data:post.featuredImage.youtubeMaxResDefaultUrl.jsonEscaped, 72, &quot;1:1&quot;) : resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)'/><b:else/><span class='thumbnail' data-src='https://resources.blogblog.com/img/blank.gif'/></b:if><b:class cond='data:post.featuredImage.isYouTube' expr:name='data:widget.sectionId == &quot;featured&quot; ? &quot;sz-1 is-ytimg&quot; : &quot;sz-2 is-ytimg&quot;'/><b:if cond='data:post.labels and (data:skin.vars.thumbtag == &quot;1px&quot;)'><span class='entry-category'><data:post.labels.first.name/></span></b:if></a>
        <div class='entry-header'>
          <h2 class='entry-title'><a expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></a></h2>
          <b:if cond='data:this.postDisplay.showSnippet and (data:widget.sectionId == &quot;featured&quot;)'><p class='entry-excerpt excerpt'><b:eval expr='data:post.snippets.long snippet { length: 164 }'/></p></b:if>
          <b:if cond='data:widgets.Blog.first.allBylineItems.author or data:widgets.Blog.first.allBylineItems.timestamp'><div class='entry-meta'><b:if cond='data:widgets.Blog.first.allBylineItems.author'><span class='entry-author mi'><b:if cond='data:widgets.Blog.first.allBylineItems.author.label'><span class='sp'><data:widgets.Blog.first.allBylineItems.author.label/></span></b:if><span class='author-name'><data:post.author.name/></span></span></b:if><b:if cond='data:widgets.Blog.first.allBylineItems.timestamp'><span class='entry-time mi'><b:if cond='data:widgets.Blog.first.allBylineItems.author and data:widgets.Blog.first.allBylineItems.timestamp.label'><span class='sp'><data:widgets.Blog.first.allBylineItems.timestamp.label/></span></b:if><time class='published' expr:datetime='data:post.date.iso8601'><data:post.date/></time></span></b:if></div></b:if>
        </div>
      </div>
    </b:includable>
    <b:includable id='contact-form-content'>
      <div class='widget-content contact-form-widget'>
        <form class='contact-form-form' name='contact-form'>
          <input class='contact-form-name cf-s' expr:ariby='data:contactFormNameMsg' expr:id='data:widget.instanceId + &quot;_contact-form-name&quot;' expr:placeholder='data:contactFormNameMsg' name='name' size='30' type='text' value=''/>
          <input class='contact-form-email cf-s' expr:ariby='data:contactFormEmailMsg + &quot; *&quot;' expr:id='data:widget.instanceId + &quot;_contact-form-email&quot;' expr:placeholder='data:contactFormEmailMsg + &quot; *&quot;' name='email' size='30' type='text' value=''/>
          <textarea class='contact-form-email-message cf-s' cols='25' expr:ariby='data:contactFormMessageMsg + &quot; *&quot;' expr:id='data:widget.instanceId + &quot;_contact-form-email-message&quot;' expr:placeholder='data:contactFormMessageMsg + &quot; *&quot;' name='email-message' rows='5'/>
          <input class='contact-form-button btn contact-form-button-submit' expr:id='data:widget.instanceId + &quot;_contact-form-submit&quot;' expr:value='data:contactFormSendMsg' type='button'/>
          <p class='contact-form-error-message' expr:id='data:widget.instanceId + &quot;_contact-form-error-message&quot;'/>
          <p class='contact-form-success-message' expr:id='data:widget.instanceId + &quot;_contact-form-success-message&quot;'/>
        </form>
      </div>
    </b:includable>
    <b:includable id='theme-variables'>
      <b:tag name='script' type='text/javascript'>var pbt={fixedMenu:<b:eval expr='data:skin.vars.fixedmenu == &quot;1px&quot; ? &quot;true&quot; : &quot;false&quot;'/>,fixedSidebar:<b:eval expr='data:skin.vars.fixedsidebar == &quot;1px&quot; ? &quot;true&quot; : &quot;false&quot;'/>,darkMode:<b:eval expr='data:skin.vars.darkmode == &quot;1px&quot; ? &quot;true&quot; : &quot;false&quot;'/>,userDarkMode:<b:eval expr='data:skin.vars.userdarkmode == &quot;1px&quot; ? &quot;true&quot; : &quot;false&quot;'/>,entryTag:<b:eval expr='data:skin.vars.entrytag == &quot;1px&quot; ? &quot;true&quot; : &quot;false&quot;'/>,thumbTag:<b:eval expr='data:skin.vars.thumbtag == &quot;1px&quot; ? &quot;true&quot; : &quot;false&quot;'/>,noTitle:&quot;<data:messages.noTitle/>&quot;,viewAll:&quot;<data:messages.viewAll/>&quot;,noResults:&quot;<data:messages.noResultsFound/>&quot;,postAuthor:<b:eval expr='data:widgets.Blog.first.allBylineItems.author ? &quot;true&quot; : &quot;false&quot;'/>,postAuthorLabel:&quot;<b:eval expr='data:widgets.Blog.first.allBylineItems.author.label ? data:widgets.Blog.first.allBylineItems.author.label : &quot;&quot;'/>&quot;,postDate:<b:eval expr='data:widgets.Blog.first.allBylineItems.timestamp ? &quot;true&quot; : &quot;false&quot;'/>,postDateLabel:&quot;<b:eval expr='data:widgets.Blog.first.allBylineItems.timestamp.label ? data:widgets.Blog.first.allBylineItems.timestamp.label : &quot;&quot;'/>&quot;}</b:tag>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='Header'>
    <b:includable id='main' var='this'>
      <b:include cond='data:imagePlacement in {&quot;REPLACE&quot;, &quot;BEFORE_DESCRIPTION&quot;}' name='image'/>
      <b:include cond='data:imagePlacement == &quot;BEHIND&quot;' name='title'/>
    </b:includable>
    <b:includable id='image'>
      <a class='logo-img' expr:href='data:blog.homepageUrl.canonical'>
        <img expr:alt='data:blog.title.escaped' expr:height='data:height' expr:src='data:image' expr:title='data:blog.title.escaped' expr:width='data:width'/>
        <b:if cond='data:view.isMultipleItems'><b:if cond='data:widget.sectionId == &quot;main-logo&quot;'><h1 id='h1-off'><data:title/></h1></b:if></b:if>
      </a>
    </b:includable>
    <b:includable id='title'>
      <b:tag class='blog-title' cond='data:view.isMultipleItems' name='h1'>
        <b:tag class='blog-title' cond='!data:view.isMultipleItems' name='span'>
          <b:tag expr:href='data:blog.homepageUrl.canonical' name='a'>
            <data:title/>
          </b:tag>
        </b:tag>
      </b:tag>
    </b:includable>
    <b:includable id='behindImageStyle'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='description'><b:comment>Replaced</b:comment></b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='LinkList'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <b:include name='linklist-content'/>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='TextList'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content'>
        <ul class='text-list list-style'>
          <b:loop values='data:items' var='item'>
            <li><data:item/></li>
          </b:loop>
        </ul>
      </div>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='HTML'>
    <b:includable id='main'>
      <b:include name='html-content'/>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='Text'>
    <b:includable id='main'>
      <b:include name='text-content'/>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='Blog'>
    <b:includable id='main' var='this'>
      <b:class cond='data:view.isMultipleItems' name='index-blog flex-col'/>
      <b:include cond='data:view.isHomepage' name='blogPostsTitle'/>
      <b:include name='searchMessage'/>
      <b:if cond='!data:posts.empty'>
        <div class='blog-posts'>
          <b:class cond='data:view.isMultipleItems' expr:name='data:skin.vars.gridstyle == &quot;1px&quot; ? &quot;index-post-wrap grid-items&quot; : &quot;index-post-wrap list-items&quot;'/>
          <b:class cond='data:view.isSingleItem' name='item-post-wrap flex-col'/>
          <b:loop index='i' values='data:posts' var='post'>
            <b:include data='post' name='postCommentsAndAd'/>
          </b:loop>
        </div>
        <b:include cond='data:view.isMultipleItems' name='ajaxPagination'/>
      </b:if>
      <b:include name='feedLinks'/>
    </b:includable>
    <b:includable id='blogPostsTitle'>
      <b:if cond='data:blog.jumpLinkMessage != &quot;{hide}&quot;'>
        <div class='main-title-wrap blog1-title'><h3 class='title'><data:blog.jumpLinkMessage/></h3><a class='title-link' href='/search'><data:messages.viewAll/></a></div>
      </b:if>
    </b:includable>
    <b:includable id='aboutPostAuthor'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='addComments'>
      <a expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'><data:messages.postAComment/></a>
    </b:includable>
    <b:includable id='ajaxPagination'>
      <!-- Ajax Pagination on Index -->
      <div class='blog-pager' id='blog-pager'>
        <b:if cond='data:olderPageUrl'>
          <a class='blog-pager-older-link load-more btn' expr:data-load='data:olderPageUrl.canonical' href='#' id='buzzspot-pro-load-more-link'><b:include data='{ message: &quot;loadMorePosts&quot; }' name='theme-custom-lang'/></a>
          <span class='loading'><div class='loader'/></span>
          <span class='no-more load-more btn'><data:messages.noResultsFound/></span>
          <b:else/>
          <span class='no-more load-more btn show'><data:messages.noResultsFound/></span>
        </b:if>
      </div>
    </b:includable>
    <b:includable id='backLinks' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='blogThisShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='bylineByName' var='byline'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='bylineRegion' var='regionItems'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentAuthorAvatar'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentDeleteIcon' var='comment'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentForm' var='post'>
      <div class='comment-form'>
        <a name='comment-form'/>
        <b:include data='post' name='commentFormIframeSrc'/>
        <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='90px' id='comment-editor' name='comment-editor' src='' width='100%'/>
        <data:post.cmtfpIframe/>
        <script type='text/javascript'>
          BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
        </script>
      </div>
    </b:includable>
    <b:includable id='commentFormIframeSrc' var='post'>
      <a expr:href='data:post.commentFormIframeSrc + &quot;&amp;skin=soho&quot;' id='comment-editor-src' rel='noopener noreferrer' title='Comment Form Link'/>
    </b:includable>
    <b:includable id='commentItem' var='comment'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentList' var='comments'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentPicker' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='comments' var='post'>
      <a name='comments'/>
      <section class='comments threaded flex-col' expr:data-embed='data:post.embedCommentForm' expr:data-num-comments='data:post.numberOfComments' id='comments'>
        <b:class expr:name='data:post.numberOfComments != 0 ? &quot;has-comments&quot; : &quot;no-comments&quot;'/>
        <b:include name='commentsTitle'/>
        <b:if cond='data:post.allowNewComments'>
          <b:if cond='data:this.messages.blogComment'><p class='comments-message excerpt'><data:this.messages.blogComment/></p></b:if>
          <b:else/>
          <b:if cond='data:post.noNewCommentsText and (data:post.numberOfComments == 0)'><p class='comments-message no-new-comments excerpt'><data:post.noNewCommentsText/><em>*</em></p></b:if>
        </b:if>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.numberOfComments != 0'>
            <div class='comments-content'>
              <div id='comment-holder'>
                <data:post.commentHtml/>
              </div>
            </div>
          </b:if>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='commentForm'/>
          </b:if>
          <b:if cond='!data:post.allowNewComments'><b:if cond='data:post.noNewCommentsText and (data:post.numberOfComments != 0)'><p class='comments-message no-new-comments excerpt'><data:post.noNewCommentsText/><em>*</em></p></b:if></b:if>
          <b:else/>
          <p class='comments-message excerpt'>Please Select Embedded Mode To Show The Comment System.<em>*</em></p>
        </b:if>
      </section>
    </b:includable>
    <b:includable id='commentsTitle'>
      <!-- Comments Title -->
      <div class='main-title-wrap comments-title'><b:class expr:name='data:this.messages.blogComment ? &quot;has-message&quot; : &quot;no-message&quot;'/><h3 class='title'><b:if cond='data:post.numberOfComments != 0'><b:if cond='data:allBylineItems.comments.label contains &quot;disqus&quot; or data:allBylineItems.comments.label contains &quot;facebook&quot;'><data:messages.postAComment/><b:else/><data:post.numberOfComments/> <data:messages.comments/></b:if><b:else/><data:messages.postAComment/></b:if></h3></div>
    </b:includable>
    <b:includable id='defaultAdUnit'>
      <ins class='adsbygoogle' data-ad-format='fluid' data-full-width-responsive='false' expr:data-ad-client='data:adClientId ?: data:blog.adsenseClientId' expr:data-ad-host='data:blog.adsenseHostId' expr:data-ad-layout-key='data:skin.vars.gridstyle != &quot;1px&quot; ? &quot;-fk-2c+dv+k-18j&quot; : &quot;-6n+e2+3n-6a+2e&quot;' expr:data-analytics-uacct='data:blog.analyticsAccountNumber' style='display:block'/>
      <script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
    </b:includable>
    <b:includable id='emailPostIcon'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='facebookShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='feedLinks'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='feedLinksBody' var='links'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='footerBylines'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='googlePlusShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='headerByline' var='post'>
      <!-- Post Entry Meta -->
      <b:if cond='data:view.isMultipleItems'>
        <b:if cond='data:allBylineItems.author or data:allBylineItems.timestamp'>
          <div class='entry-meta'>
            <b:class cond='data:skin.vars.gridstyle == &quot;1px&quot; and (data:skin.vars.summary == &quot;1px&quot;)' name='has-snip'/>
            <b:include cond='data:allBylineItems.author' data='post' name='postAuthor'/>
            <b:include cond='data:allBylineItems.timestamp' data='post' name='postTimestamp'/>
          </div>
        </b:if>
      </b:if>
      <b:if cond='data:view.isPost'>
        <b:if cond='data:allBylineItems.author or data:allBylineItems.timestamp or data:allBylineItems.share'>
          <b:class name='has-meta'/>
          <div class='entry-meta'>
            <div class='align-left'>
              <b:class cond='data:allBylineItems.timestamp' name='has-time'/>
              <b:if cond='data:allBylineItems.author'><span class='entry-avatar'><span class='avatar' expr:data-src='data:post.author.authorPhoto.image ? resizeImage(data:post.author.authorPhoto.image, 72, &quot;1:1&quot;) : &quot;https://1.bp.blogspot.com/-QN2lgvtYZco/YN3mUSryAVI/AAAAAAAAADs/KrR-etCcvUMcPl06jopTs9pzq59IAXhMQCLcBGAsYHQ/s72-c/avatar.jpg&quot;'/></span></b:if>
              <b:tag class='al-items' cond='data:allBylineItems.author and data:allBylineItems.timestamp' name='div'>
              <b:include cond='data:allBylineItems.author' data='post' name='postAuthor'/>
              <b:include cond='data:allBylineItems.timestamp' data='post' name='postTimestamp'/>
              </b:tag>
            </div>
            <b:if cond='data:allBylineItems.share'>
              <div class='align-right'>
                <button class='share-toggle btn' expr:aria-label='data:messages.share'/>
              </div>
            </b:if>
          </div>
        </b:if>
      </b:if>
    </b:includable>
    <b:includable id='homePageLink'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='iframeComments' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='indexPost' var='post'>
      <!-- Index Post Content -->
      <b:include data='post' name='postFeaturedImage'/>
      <div class='entry-header'>
        <b:include cond='data:skin.vars.entrytag == &quot;1px&quot; and (data:skin.vars.gridstyle != &quot;1px&quot;)' data='post' name='postCategory'/>
        <b:include data='post' name='postHeader'/>
        <b:include cond='data:skin.vars.summary == &quot;1px&quot;' data='post' name='postBodySnippet'/>
        <b:include data='post' name='headerByline'/>
      </div>
    </b:includable>
    <b:includable id='inlineAd' var='post'>
      <b:if cond='!data:view.isPreview'>
        <b:if cond='data:i != 0'>
          <b:if cond='data:post.includeAd and data:post.adNumber'>
            <b:if cond='data:this.adCode or data:this.adClientId or data:blog.adsenseClientId'>
              <div class='post ad-type'>
                <div class='inline-ad-wrap'>
                  <div class='inline-ad'>
                    <b:if cond='data:this.adCode != &quot;&quot;'>
                      <data:this.adCode/>
                      <b:else/>
                      <b:if cond='data:this.adClientId or data:blog.adsenseClientId'>
                        <b:include name='defaultAdUnit'/>
                      </b:if>
                    </b:if>
                  </div>
                </div>
              </div>
            </b:if>
          </b:if>
        </b:if>
      </b:if>
    </b:includable>
    <b:includable id='itemPost' var='post'>
      <!-- Item Post Content -->
      <b:include data='post' name='postMeta'/>
      <div class='item-post-inner flex-col'>
        <div class='entry-header p-eh'>
          <b:include data='post' name='postHeader'/>
        </div>
        <div class='entry-content-wrap flex-col'>
          <b:include data='post' name='postBody'/>
          <b:include cond='data:view.isPost and data:allBylineItems.labels' data='post' name='postLabels'/>
        </div>
        <b:include cond='data:view.isPost and data:allBylineItems.share' data='post' name='postShareButtons'/>
      </div>
      <b:include cond='data:view.isPost' data='post' name='postFooter'/>
    </b:includable>
    <b:includable id='linkShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='nextPageLink'>
      <b:if cond='data:olderPageUrl'>
        <a class='post-nav-link post-nav-older-link' expr:href='data:olderPageUrl.canonical'>
          <b:include data='{ message: &quot;nextPost&quot; }' name='theme-custom-lang'/>
        </a>
        <b:else/>
        <span class='post-nav-link post-nav-older-link'>
          <b:include data='{ message: &quot;nextPost&quot; }' name='theme-custom-lang'/>
        </span>
      </b:if>
    </b:includable>
    <b:includable id='otherSharingButton'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='platformShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='post' var='post'>
      <!-- Index Posts -->
      <b:if cond='data:view.isMultipleItems'>
        <b:include data='post' name='indexPost'/>
      </b:if>
      <!-- Item Post -->
      <b:if cond='data:view.isSingleItem'>
        <b:include data='post' name='itemPost'/>
      </b:if>
    </b:includable>
    <b:includable id='postAuthor' var='post'>
      <!-- Post Author -->
      <span class='entry-author mi'><b:if cond='data:allBylineItems.author.label'><span class='by sp'><data:allBylineItems.author.label/></span></b:if><span class='author-name'><data:post.author.name/></span></span>
    </b:includable>
    <b:includable id='postBody' var='post'> 
      <!-- Ads before post content. -->
      <b:if cond='data:view.isPost'><b:tag cond='data:widgets any w =&gt; w.sectionId == &quot;buzzspot-pro-main-before-ad&quot;' id='before-ad' name='div'/></b:if>
      <!-- Post Body Entry Content-->
      <div class='post-body entry-content' id='post-body'>
        <data:post.body/>
      </div>
      <!-- Ads after post content. -->
      <b:if cond='data:view.isPost'><b:tag cond='data:widgets any w =&gt; w.sectionId == &quot;buzzspot-pro-main-after-ad&quot;' id='after-ad' name='div'/></b:if>
    </b:includable>
    <b:includable id='postBodySnippet' var='post'><p class='entry-excerpt excerpt'><b:eval expr='data:post.snippets.long snippet { length: 88 }'/></p></b:includable>
    <b:includable id='postBreadcrumbs' var='post'>
      <!-- Post Breadcrumbs -->
      <b:if cond='data:view.isPost'>
        <b:if cond='data:skin.vars.breadcrumb == &quot;1px&quot;'><nav id='breadcrumb'><a class='home' expr:href='data:blog.homepageUrl'><data:messages.home/></a><b:if cond='data:post.labels'><em class='separator'/><a class='label' expr:href='data:post.labels.first.url'><data:post.labels.first.name/></a></b:if></nav></b:if>
        <script type='application/ld+json'>{&quot;@context&quot;:&quot;http://schema.org&quot;,&quot;@type&quot;:&quot;BreadcrumbList&quot;,&quot;itemListElement&quot;:[{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:1,&quot;name&quot;:&quot;<data:messages.home.jsonEscaped/>&quot;,&quot;item&quot;:&quot;<data:blog.homepageUrl.canonical.jsonEscaped/>&quot;},{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:2,&quot;name&quot;:&quot;<b:if cond='data:post.labels'><data:post.labels.first.name.jsonEscaped/><b:else/><data:messages.posts/></b:if>&quot;,&quot;item&quot;:&quot;<b:if cond='data:post.labels'><data:post.labels.first.url.canonical.jsonEscaped/><b:else/><b:eval expr='data:blog.homepageUrl.canonical.jsonEscaped + &quot;search/&quot;'/></b:if>&quot;},{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:3,&quot;name&quot;:&quot;<data:post.title.jsonEscaped/>&quot;,&quot;item&quot;:&quot;<data:post.url.canonical.jsonEscaped/>&quot;}]}</script>
      </b:if>
      <b:if cond='data:view.isPage'>
        <script type='application/ld+json'>{&quot;@context&quot;:&quot;http://schema.org&quot;,&quot;@type&quot;:&quot;BreadcrumbList&quot;,&quot;itemListElement&quot;:[{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:1,&quot;name&quot;:&quot;<data:messages.home.jsonEscaped/>&quot;,&quot;item&quot;:&quot;<data:blog.homepageUrl.canonical.jsonEscaped/>&quot;},{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:2,&quot;name&quot;:&quot;<data:post.title.jsonEscaped/>&quot;,&quot;item&quot;:&quot;<data:post.url.canonical.jsonEscaped/>&quot;}]}</script>
      </b:if>
    </b:includable>
    <b:includable id='postCategory' var='post'>
      <!-- Post Label -->
      <b:if cond='data:post.labels'><span class='entry-category'><data:post.labels.first.name/></span></b:if>
    </b:includable>
    <b:includable id='postCommentsAndAd' var='post'>
      <!-- In-Feed Ads -->
      <b:include cond='data:view.isMultipleItems and not data:view.search.label and not data:view.search.query and not data:view.isArchive' data='post' name='inlineAd'/>
      <article>
        <b:class cond='data:view.isMultipleItems' expr:name='data:skin.vars.gridstyle == &quot;1px&quot; ? &quot;post hentry item-&quot; + data:i : &quot;post hentry item-&quot; + data:i'/>
        <b:class cond='data:view.isSingleItem' name='item-post hentry flex-col'/>
        <b:include data='post' name='post'/>
      </article>
      <b:if cond='data:view.isSingleItem and data:post.allowComments'>
        <!-- Post Comments -->
        <div class='buzzspot-pro-blog-post-comments post-widget' expr:data-shortcode='data:allBylineItems.comments.label contains &quot;type&quot; ? data:allBylineItems.comments.label : &quot;$type={blogger}&quot;'>
          <b:include data='post' name='threadedCommentsDisqus'/>
          <b:include data='post' name='comments'/>
        </div>
      </b:if>
      <!-- Post Navigation -->
      <b:include cond='data:skin.vars.postnav == &quot;1px&quot;' name='postPagination'/>
    </b:includable>
    <b:includable id='postCommentsLink'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postFeaturedImage' var='post'>
      <!-- Post Featured Image -->
      <a class='entry-thumbnail' expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><b:if cond='data:post.featuredImage'><span class='thumbnail' expr:data-src='data:post.featuredImage.isYouTube ? resizeImage(data:post.featuredImage.youtubeMaxResDefaultUrl.jsonEscaped, 72, &quot;1:1&quot;) : resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)'/><b:else/><span class='thumbnail' data-src='https://resources.blogblog.com/img/blank.gif'/></b:if><b:class cond='data:post.featuredImage.isYouTube' name='is-ytimg'/><b:include cond='data:skin.vars.thumbtag == &quot;1px&quot; and (data:skin.vars.gridstyle == &quot;1px&quot;)' data='post' name='postCategory'/></a>
    </b:includable>
    <b:includable id='postFooter' var='post'>
      <!-- Post Footer Items -->
      <b:tag class='post-footer flex-col' cond='data:post.author.aboutMe or (data:widgets.HTML any w =&gt; w.sectionId == &quot;buzzspot-pro-related-posts&quot;) or (data:widgets any w =&gt; w.sectionId == &quot;buzzspot-pro-post-footer-ads&quot;)' name='footer'>
        <b:include cond='data:post.author.aboutMe' data='post' name='postFooterAuthorProfile'/>
        <b:include cond='data:widgets.HTML any w =&gt; w.sectionId == &quot;buzzspot-pro-related-posts&quot;' data='post' name='relatedPosts'/>
        <b:tag class='post-widget' cond='data:widgets any w =&gt; w.sectionId == &quot;buzzspot-pro-post-footer-ads&quot;' id='post-footer-ads' name='div'/>
      </b:tag>
    </b:includable>
    <b:includable id='postFooterAuthorProfile' var='post'>
      <div class='about-author post-widget'>
        <div class='author-avatar entry-avatar'>
          <span class='avatar' expr:data-src='data:post.author.authorPhoto.image ? resizeImage(data:post.author.authorPhoto.image, 72, &quot;1:1&quot;) : &quot;https://1.bp.blogspot.com/-QN2lgvtYZco/YN3mUSryAVI/AAAAAAAAADs/KrR-etCcvUMcPl06jopTs9pzq59IAXhMQCLcBGAsYHQ/s72-c/avatar.jpg&quot;'/>
        </div>
        <div class='author-description flex-col'>
          <h3 class='author-title'><b:tag cond='data:post.author.profileUrl' expr:alt='data:post.author.name' expr:href='data:post.author.profileUrl' name='a' rel='noopener noreferrer' target='_blank'><data:post.author.name/></b:tag></h3>
          <p class='author-text excerpt'><data:post.author.aboutMe/></p>
        </div>
      </div>
    </b:includable>
    <b:includable id='postHeader' var='post'>
      <b:include cond='data:view.isSingleItem' data='post' name='postBreadcrumbs'/>
      <b:include data='post' name='postTitle'/>
      <b:include cond='data:view.isPost' data='post' name='headerByline'/>
    </b:includable>
    <b:includable id='postJumpLink' var='post'>
      <b:if cond='data:blog.jumpLinkMessage != &quot;hide&quot;'>
        <a class='read-more' expr:href='data:post.url.canonical'><data:blog.jumpLinkMessage/></a>
      </b:if>
    </b:includable>
    <b:includable id='postLabels' var='post'>
      <b:if cond='data:post.labels'>
        <div class='entry-labels'>
          <b:if cond='data:allBylineItems.labels.label'><span class='labels-label btn'><data:allBylineItems.labels.label/></span></b:if>
          <b:loop values='data:post.labels' var='label'>
            <a class='label-link btn' expr:href='data:label.url' rel='tag'><data:label.name/></a>
          </b:loop>
        </div>
      </b:if>
    </b:includable>
    <b:includable id='postLocation'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postMeta' var='post'>
      <b:if cond='data:view.isPost'>
        <script type='application/ld+json'>{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;NewsArticle&quot;,&quot;mainEntityOfPage&quot;:{&quot;@type&quot;:&quot;WebPage&quot;,&quot;@id&quot;:&quot;<data:post.url.canonical.jsonEscaped/>&quot;},&quot;headline&quot;:&quot;<data:post.title.jsonEscaped/>&quot;,&quot;description&quot;:&quot;<data:post.snippets.short.jsonEscaped/>&quot;,&quot;datePublished&quot;:&quot;<data:post.date.iso8601.jsonEscaped/>&quot;,&quot;dateModified&quot;:&quot;<data:post.lastUpdated.iso8601.jsonEscaped/>&quot;,&quot;image&quot;:{&quot;@type&quot;:&quot;ImageObject&quot;,<b:if cond='data:post.featuredImage.isResizable'>&quot;url&quot;:&quot;<b:eval expr='resizeImage(data:post.featuredImage, 1200, &quot;1200:675&quot;)'/>&quot;,&quot;height&quot;:675,&quot;width&quot;:1200<b:else/>&quot;url&quot;:&quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=w1200&quot;,&quot;height&quot;:348,&quot;width&quot;:1200</b:if>},&quot;author&quot;:{&quot;@type&quot;:&quot;Person&quot;,&quot;name&quot;:&quot;<data:post.author.name.jsonEscaped/>&quot;},&quot;publisher&quot;:{&quot;@type&quot;:&quot;Organization&quot;,&quot;name&quot;:&quot;Blogger&quot;,&quot;logo&quot;:{&quot;@type&quot;:&quot;ImageObject&quot;,&quot;url&quot;:&quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=h60&quot;,&quot;width&quot;:206,&quot;height&quot;:60}}}</script>
      </b:if>
    </b:includable>
    <b:includable id='postMetadataJSONImage'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postMetadataJSONPublisher'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postPagination'>
      <b:if cond='data:view.isPost'>
        <div class='post-nav post-widget'>
          <b:include name='previousPageLink'/>
          <b:include name='nextPageLink'/>
        </div>
      </b:if>
    </b:includable>
    <b:includable id='postReactions'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postShareButtons' var='post'>
      <!-- Post Share Buttons & Modal -->
      <div class='post-share'>
        <ul class='share-a social sb-a'>
          <li class='share-label'><span class='sl-btn btn'><i class='sl-ico'/></span></li>
          <li class='facebook has-span'><a class='fa-facebook btn pbt-window' data-height='500' data-width='520' expr:data-url='&quot;https://www.facebook.com/sharer.php?u=&quot; + data:post.url.canonical' href='#' rel='noopener noreferrer' title='Facebook'><span>Facebook</span></a></li>
          <li class='twitter has-span'><a class='fa-twitter btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://twitter.com/intent/tweet?url=&quot; + data:post.url.canonical + &quot;&amp;text=&quot; + data:post.title.jsEscaped' href='#' rel='noopener noreferrer' title='Twitter'><span>Twitter</span></a></li>
          <li class='whatsapp'><a class='fa-whatsapp btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://api.whatsapp.com/send?text=&quot; + data:post.title.jsEscaped + &quot; | &quot; + data:post.url.canonical' href='#' rel='noopener noreferrer' title='WhatsApp'/></li>
          <li class='email'><a class='fa-email btn pbt-window' data-height='500' data-width='520' expr:data-url='&quot;mailto:?subject=&quot; + data:post.title.jsEscaped + &quot;&amp;body=&quot; + data:post.url.canonical' href='#' rel='noopener noreferrer' title='Email'/></li>
          <li class='show-more'><button class='btn' expr:aria-label='data:messages.showMore'/></li>
        </ul>
        <div class='share-modal'>
          <div class='modal-inner'>
            <div class='modal-header'>
              <span class='modal-thumb entry-thumbnail'><b:if cond='data:post.featuredImage'><span class='thumbnail' expr:data-src='data:post.featuredImage.isYouTube ? resizeImage(data:post.featuredImage.youtubeMaxResDefaultUrl.jsonEscaped, 72, &quot;1:1&quot;) : resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)'/><b:else/><span class='entry-thumbnail' data-src='https://resources.blogblog.com/img/blank.gif'/></b:if><b:class cond='data:post.featuredImage.isYouTube' name='sz-5 is-ytimg'/></span>
              <span class='modal-title'><span class='strong'><data:messages.share/>:</span><span class='title'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></span></span>
            </div>
            <ul class='share-b social sb-a'>
              <li class='facebook'><a class='fa-facebook btn pbt-window' data-height='500' data-width='520' expr:data-url='&quot;https://www.facebook.com/sharer.php?u=&quot; + data:post.url.canonical' href='#' rel='noopener noreferrer' title='Facebook'><span>Facebook</span></a></li>
              <li class='twitter'><a class='fa-twitter btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://twitter.com/intent/tweet?url=&quot; + data:post.url.canonical + &quot;&amp;text=&quot; + data:post.title.jsEscaped' href='#' rel='noopener noreferrer' title='Twitter'><span>Twitter</span></a></li>
              <li class='whatsapp'><a class='fa-whatsapp btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://api.whatsapp.com/send?text=&quot; + data:post.title.jsEscaped + &quot; | &quot; + data:post.url.canonical' href='#' rel='noopener noreferrer' title='WhatsApp'><span>WhatsApp</span></a></li>
              <li class='pinterest-p'><a class='fa-pinterest-p btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://www.pinterest.com/pin/create/button/?url=&quot; + data:post.url.canonical + &quot;&amp;media=&quot; + data:post.featuredImage + &quot;&amp;description=&quot; + data:post.title.jsEscaped' href='#' rel='noopener noreferrer' title='Pinterest'><span>Pinterest</span></a></li>
              <li class='linkedin'><a class='fa-linkedin-in btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://www.linkedin.com/shareArticle?mini=true&amp;url=&quot; + data:post.url.canonical + &quot;&amp;title=&quot; + data:post.title.jsEscaped' href='#' rel='noopener noreferrer' title='LinkedIn'><span>LinkedIn</span></a></li>
              <li class='reddit'><a class='fa-reddit-alien btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://reddit.com/submit?url=&quot; + data:post.url.canonical + &quot;&amp;title=&quot; + data:post.title.jsEscaped' href='#' rel='noopener noreferrer' title='Reddit'><span>Reddit</span></a></li>
              <li class='tumblr'><a class='fa-tumblr btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://www.tumblr.com/share/link?url=&quot; + data:post.url.canonical + &quot;&amp;name=&quot; + data:post.title.jsEscaped' href='#' rel='noopener noreferrer' title='Tumblr'><span>Tumblr</span></a></li>
              <li class='telegram'><a class='fa-telegram-plane btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://telegram.me/share/url?url=&quot; + data:post.url.canonical + &quot;&amp;text=&quot; + data:post.title.jsEscaped' href='#' rel='noopener noreferrer' title='Telegram'><span>Telegram</span></a></li>
              <li class='email'><a class='fa-email btn pbt-window' data-height='500' data-width='520' expr:data-url='&quot;mailto:?subject=&quot; + data:post.title.jsEscaped + &quot;&amp;body=&quot; + data:post.url.canonical' href='#' rel='noopener noreferrer' title='Email'><span>Email</span></a></li>
            </ul>
          </div>
          <button class='hide-modal' expr:aria-label='data:messages.showLess'/>
        </div>
        <b:tag class='overlay' id='share-overlay' name='div'/>
      </div>
    </b:includable>
    <b:includable id='postTimestamp' var='post'>
      <!-- Post Timestamp -->
      <span class='entry-time mi'><b:if cond='data:allBylineItems.author and data:allBylineItems.timestamp.label'><span class='sp'><data:allBylineItems.timestamp.label/></span></b:if><time class='published' expr:datetime='data:post.date.iso8601'><data:post.date/></time></span>
    </b:includable>
    <b:includable id='postTitle' var='post'>
      <!-- Post Title Index and Item -->
      <b:if cond='data:view.isMultipleItems'>
        <h2 class='entry-title'><a expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle' rel='bookmark'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></a></h2>
      </b:if>
      <b:if cond='data:view.isSingleItem'>
        <h1 class='entry-title'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></h1>
      </b:if>
    </b:includable>
    <b:includable id='previousPageLink'>
      <b:if cond='data:newerPageUrl'>
        <a class='post-nav-link post-nav-newer-link' expr:href='data:newerPageUrl.canonical'>
          <b:include data='{ message: &quot;prevPost&quot; }' name='theme-custom-lang'/>
        </a>
        <b:else/>
        <span class='post-nav-link post-nav-newer-link'>
          <b:include data='{ message: &quot;prevPost&quot; }' name='theme-custom-lang'/>
        </span>
      </b:if>
    </b:includable>
    <b:includable id='relatedPosts' var='post'>
      <!-- Related Posts -->
      <div class='post-widget' id='related-wrap'>
        <div class='main-title-wrap related-title'>
          <b:with value='data:widgets.HTML filter (w =&gt; w.sectionId == &quot;buzzspot-pro-related-posts&quot;) map (w =&gt; w.title)' var='pbtTitle'>
            <h3 class='title'><b:eval expr='data:pbtTitle.first ? data:pbtTitle.first : data:messages.youMayLikeThesePosts'/></h3>
          </b:with>
          <a class='title-link' expr:href='data:post.labels ? data:post.labels.first.url : &quot;/search&quot;'><data:messages.viewAll/></a>
        </div>
        <div class='related-content'>
          <b:if cond='data:post.labels'>
            <div class='related-tag' expr:data-id='data:post.id' expr:data-label='data:post.labels.first.name'/>
            <b:else/>
            <div class='related-tag' data-label='recent' expr:data-id='data:post.id'/>
          </b:if>
        </div> 
      </div>  
    </b:includable>
    <b:includable id='searchMessage'>
      <!-- Search Message -->
      <b:if cond='data:posts.empty'>
        <b:class name='no-posts'/>
      </b:if>
      <b:if cond='data:view.search.query'>
        <div class='queryMessage'>
          <b:if cond='data:posts.empty'>
            <span class='query-info query-error'>&quot;<data:view.search.query/>&quot;</span>
            <b:else/>
            <span class='query-info query-success'>&quot;<data:view.search.query/>&quot;</span>
          </b:if>
        </div>
      </b:if>
      <b:if cond='data:view.search.label'>
        <div class='queryMessage '>
          <b:if cond='data:posts.empty'>
            <span class='query-info query-label query-error'><data:view.search.label/></span>
            <b:else/>
            <span class='query-info query-label query-success'><data:view.search.label/></span>
          </b:if>
        </div>
      </b:if>
      <b:if cond='data:view.isArchive'>
        <div class='queryMessage'>
          <b:if cond='data:posts.empty'>
            <span class='query-info query-error'><data:view.archive.rangeMessage/></span>
            <b:else/>
            <span class='query-info query-success'><data:view.archive.rangeMessage/></span>
          </b:if>
        </div>
      </b:if>
      <b:if cond='data:view.isError'>
        <div class='errorWrap'>
          <h3>404</h3>
          <h4><data:messages.theresNothingHere/></h4>
          <p><data:navMessage/></p>
          <a class='homepage btn' expr:href='data:blog.homepageUrl'><data:messages.home/></a>
        </div>
      </b:if>
      <b:if cond='data:view.isMultipleItems and data:posts.empty'><div class='queryEmpty'><data:messages.noResultsFound/></div></b:if>
    </b:includable>
    <b:includable id='sharingButton'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtonContent'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtons'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtonsMenu'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingPlatformIcon'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='threadedCommentForm' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='threadedCommentJs' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='threadedComments' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='threadedCommentsDisqus' var='post'>
      <script type='text/javascript'>
        var disqus_shortname = &quot;probloggertemplates&quot;;
        var disqus_blogger_current_url = &quot;<data:post.url.canonical/>&quot;;
        if (!disqus_blogger_current_url.length) {
          disqus_blogger_current_url = &quot;<data:post.url.canonical/>&quot;;
        }
        var disqus_blogger_homepage_url = &quot;<data:blog.canonicalHomepageUrl/>&quot;;
        var disqus_blogger_canonical_homepage_url = &quot;<data:blog.canonicalHomepageUrl/>&quot;;
      </script>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='PopularPosts'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <div class='widget-content'>
        <b:if cond='data:widget.sectionId == &quot;ticker&quot;'>
          <div class='pbt-ticker ticker-items'>
            <b:loop index='i' values='data:posts' var='post'>
              <b:include data='post' name='content'/>
            </b:loop>
          </div>
        <b:elseif cond='data:widget.sectionId == &quot;trending&quot;'/>
          <div class='trending-items'>
            <b:loop index='i' values='data:posts' var='post'>
              <b:include cond='data:i lt 4' data='post' name='content'/>
            </b:loop>
          </div>
          <b:else/>
          <b:class name='side-items'/>
          <b:loop index='i' values='data:posts' var='post'>
            <b:include data='post' name='content'/>
          </b:loop>
        </b:if>
      </div>
    </b:includable>
    <b:includable id='blogThisShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='bylineByName' var='byline'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='bylineRegion' var='regionItems'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentsLink'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentsLinkIframe'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='content' var='post'>
      <b:include name='popular-content'/>
    </b:includable>
    <b:includable id='emailPostIcon'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='facebookShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='footerBylines'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='googlePlusShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='headerByline'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='linkShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='otherSharingButton'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='platformShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postAuthor'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postCommentsLink'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postJumpLink' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postLabels'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postLocation'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postReactions'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postShareButtons'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postTimestamp'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButton'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtonContent'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtons'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtonsMenu'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingPlatformIcon'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostByline'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostContent'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostThumbnail'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostTitle'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPosts'><b:comment>Replaced</b:comment></b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='FeaturedPost'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <div class='widget-content'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='content'/>
        </b:loop>
      </div>
    </b:includable>
    <b:includable id='blogThisShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='bylineByName' var='byline'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='bylineRegion' var='regionItems'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentsLink'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='commentsLinkIframe'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='content' var='post'>
      <b:include name='featured-content'/>
    </b:includable>
    <b:includable id='emailPostIcon'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='facebookShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='footerBylines'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='googlePlusShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='headerByline'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='linkShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='otherSharingButton'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='platformShare'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postAuthor'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postCommentsLink'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postJumpLink' var='post'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postLabels'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postLocation'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postReactions'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postShareButtons'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='postTimestamp'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButton'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtonContent'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtons'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingButtonsMenu'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='sharingPlatformIcon'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostByline'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostContent'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostThumbnail'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPostTitle'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='snippetedPosts'><b:comment>Replaced</b:comment></b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='ContactForm'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <b:include name='contact-form-content'/>
    </b:includable>       
  </b:defaultmarkup>
  <b:defaultmarkup type='Label'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content'>
        <b:class expr:name='data:this.display + &quot;-label&quot;'/>
        <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
        <b:include cond='data:this.display == &quot;cloud&quot;' name='cloud'/>
      </div>
    </b:includable>
    <b:includable id='list'>
      <ul class='list-style'>
        <b:loop values='data:labels' var='label'>
          <li><a class='label-name' expr:href='data:label.url'><data:label.name/><b:if cond='data:this.showFreqNumbers'><b:class name='has-count'/><span class='label-count count-style'>(<data:label.count/>)</span></b:if></a></li>
        </b:loop>
      </ul>
    </b:includable>
    <b:includable id='cloud'>
      <ul class='cloud-style'>
        <b:loop values='data:labels' var='label'>
          <li><a class='label-name btn' expr:href='data:label.url'><data:label.name/><b:if cond='data:this.showFreqNumbers'><b:class name='has-count'/><span class='label-count count-style'>(<data:label.count/>)</span></b:if></a></li>
        </b:loop>
      </ul>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='FollowByEmail'>
    <b:includable id='main' var='this'>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content'>
		<p>This gadget is no longer available.</p>
      </div>
    </b:includable>
  </b:defaultmarkup> 
  <b:defaultmarkup type='Image'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <b:include name='image-content'/>
    </b:includable>
  </b:defaultmarkup> 
  <b:defaultmarkup type='BlogArchive'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <div class='widget-content'>
        <b:class name='archive-list'/>
        <b:include cond='data:this.style in {&quot;FLAT&quot;, &quot;MENU&quot;, &quot;HIERARCHY&quot;}' name='flat'/>
      </div>
    </b:includable>
    <b:includable id='flat'>
      <ul class='list-style'>
        <b:loop values='data:data' var='i'>
          <li><a class='archive-name' expr:href='data:i.url'><data:i.name/><b:if cond='data:i.post-count'><b:class name='has-count'/><span class='archive-count count-style'>(<data:i.post-count/>)</span></b:if></a></li>
        </b:loop>
      </ul>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='PageList'>
    <b:includable id='main'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <b:include name='pagelist-content'/>
    </b:includable>
    <b:includable id='overflowButton'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='overflowablePageList'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='pageLink'><b:comment>Replaced</b:comment></b:includable>
    <b:includable id='pageList'><b:comment>Replaced</b:comment></b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='BlogSearch'>
    <b:includable id='main'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='content'>
      <b:include name='searchForm'/>
    </b:includable>
    <b:includable id='searchForm'>
      <form class='search-form' expr:action='data:blog.searchUrl'>
        <b:attr cond='!data:view.isPreview' name='target' value='_top'/>
        <b:include name='urlParamsAsFormInput'/>
        <input autocomplete='off' class='search-input' expr:aria-label='data:messages.search' expr:placeholder='data:messages.search' name='q' type='search' value=''/>
        <b:include name='searchSubmit'/>
      </form>
    </b:includable>
    <b:includable id='searchSubmit'>
      <input class='search-action btn' expr:value='data:messages.ok' type='submit'/>
    </b:includable>
  </b:defaultmarkup>
  <b:defaultmarkup type='Profile'>
    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
    <b:includable id='authorProfileImage' var='this'>
      <img class='profile-img' expr:alt='data:messages.myPhoto' expr:src='resizeImage(data:authorPhoto.image, 50, &quot;1:1&quot;)'/>
    </b:includable>
    <b:includable id='defaultProfileImage' var='this'>
      <img class='profile-img' expr:alt='data:messages.myPhoto' src='https://1.bp.blogspot.com/-QN2lgvtYZco/YN3mUSryAVI/AAAAAAAAADs/KrR-etCcvUMcPl06jopTs9pzq59IAXhMQCLcBGAsYHQ/w50-h50-p-k-no-nu/avatar.jpg'/>
    </b:includable>
    <b:includable id='userProfileInfo' var='this'>
      <div class='profile-info'>
        <dl class='profile-datablock'>
          <b:include name='userProfileData'/>
        </dl>
        <b:include name='viewProfileLink'/>
      </div>
    </b:includable>
    <b:includable id='teamProfileLink' var='this'>
      <b:include name='profileImage'/>
      <div class='profile-info'>
        <a class='profile-name' expr:href='data:userUrl' rel='noopener nofollow' target='_blank'><data:display-name/></a>
        <a class='profile-link' expr:href='data:userUrl' rel='noopener nofollow' target='_blank'><data:messages.showMore/></a>
      </div>
    </b:includable>
    <b:includable id='userProfile' var='this'>
      <b:include name='profileImage'/>
      <div class='profile-info'>
        <a class='profile-name' expr:href='data:userUrl' rel='noopener nofollow' target='_blank'><data:displayname/></a>
        <a class='profile-link' expr:href='data:userUrl' rel='noopener nofollow' target='_blank'><data:messages.showMore/></a>
      </div>
    </b:includable>
  </b:defaultmarkup>
</b:defaultmarkups>
</head>
<body>
<b:include name='theme-body-class'/>
<b:if cond='data:view.isLayoutMode or (data:widgets any w =&gt; w.sectionId == &quot;pbt-panel&quot;)'>
  <!-- Theme Options -->
  <div id='theme-options' style='display:none'>
    <b:section class='pbt-panel' id='pbt-panel' maxwidgets='2' name='Theme Options' showaddelement='no'>
      <b:widget id='Image52' locked='true' title='Default Thumbnail' type='Image' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='displayUrl'>https://blogger.googleusercontent.com/img/a/AVvXsEjZHN_IFmJTxG3qth54NgzhRnKu1nT4kXpL23ylcpDHjVkm0UpT1gy85O3V1slexNwVEclc49dr81ky-bZvZo9cgKVAwoRtZZ-eavImy9dPUeiSrfQfL63xfXZDx0B3xriEJvQm9SFJeZBAVYPKpbzKkvuBYvSdF7Hpk7inDsHZDgM9ThY7oB3pcjEoTOkH=s688</b:widget-setting>
          <b:widget-setting name='displayHeight'>688</b:widget-setting>
          <b:widget-setting name='sectionWidth'>150</b:widget-setting>
          <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
          <b:widget-setting name='displayWidth'>688</b:widget-setting>
          <b:widget-setting name='link'/>
          <b:widget-setting name='caption'/>
        </b:widget-settings>
        <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
        <b:includable id='content'>
      <b:include name='image-content'/>
    </b:includable>
      </b:widget>
      <b:widget id='HTML50' locked='true' title='JSON Variables' type='HTML' visible='true'>
        <b:widget-settings>
          <b:widget-setting name='content'/>
        </b:widget-settings>
        <b:includable id='main'>
      <b:include name='html-content'/>
    </b:includable>
      </b:widget>
    </b:section>
  </div>
</b:if>
<!-- Site Content -->
<div id='outer-wrapper'>
  <b:if cond='data:view.isLayoutMode or (data:view.isHomepage or (data:view.isPost and (data:skin.vars.topad_onpost == &quot;1px&quot;))) and (data:widgets any w =&gt; w.sectionId == &quot;top-ads&quot;)'>
    <div class='flex-c' id='top-ads-wrap'>
      <b:class cond='data:skin.vars.topad_border == &quot;1px&quot;' name='has-border'/>
      <b:section class='top-ads container row-x1' id='top-ads' maxwidgets='1' name='Top ADS' showaddelement='yes'/>
    </div>
  </b:if>
  <header id='header-wrapper'>
    <div class='main-header'>
      <div class='header-inner'>
        <div class='header-header flex-c'>
          <div class='container row-x1'>
            <div class='header-items'>
              <div class='flex-left'>
                <b:tag aria-label='Show Menu' class='mobile-menu-toggle' name='button'/>
                <b:if cond='data:view.isLayoutMode or (data:widgets.Image any w =&gt; w.sectionId == &quot;main-logo&quot;)'>
                  <b:section class='main-logo' id='main-logo' maxwidgets='1' name='Header Logo' showaddelement='no'>
                    <b:widget id='Image50' locked='true' title='' type='Image' visible='true'>
                      <b:widget-settings>
                        <b:widget-setting name='displayUrl'>https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEj3x0k1nEamHqcggzCkFqE6CtmLkCZ-qD6x8xu9zt4KB0nlRO0M5Ec6aAoAVXFz7ex8z46L9g669iTxaWjkHKd8JnLF6bBcMDA8kFv1nLI5BY-IKpSLkdwcBZiUXE4lThybI_j3lDsLIrKD1kfvC-vlKbNOgB0GTVigLr_8geqnFyNRbNVimty5BxosqGX_/s320/Picsart_23-08-15_14-04-25-406.png</b:widget-setting>
                        <b:widget-setting name='displayHeight'>81</b:widget-setting>
                        <b:widget-setting name='sectionWidth'>150</b:widget-setting>
                        <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
                        <b:widget-setting name='displayWidth'>320</b:widget-setting>
                        <b:widget-setting name='link'>https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEj3x0k1nEamHqcggzCkFqE6CtmLkCZ-qD6x8xu9zt4KB0nlRO0M5Ec6aAoAVXFz7ex8z46L9g669iTxaWjkHKd8JnLF6bBcMDA8kFv1nLI5BY-IKpSLkdwcBZiUXE4lThybI_j3lDsLIrKD1kfvC-vlKbNOgB0GTVigLr_8geqnFyNRbNVimty5BxosqGX_/s16000/Picsart_23-08-15_14-04-25-406.png</b:widget-setting>
                        <b:widget-setting name='caption'/>
                      </b:widget-settings>
                      <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
                      <b:includable id='content'>
      <b:include name='image-content'/>
    </b:includable>
                    </b:widget>
                  </b:section>
                <b:else/>
                  <div class='main-logo'>
                    <b:tag class='title' expr:name='data:view.isMultipleItems ? &quot;h1&quot; : &quot;span&quot;'>
                      <a class='homepage' expr:href='data:blog.homepageUrl.canonical' rel='home'><data:blog.title/></a>
                    </b:tag>
                  </div>
                </b:if>
                <b:section class='buzzspot-pro-main-menu' id='buzzspot-pro-main-menu' maxwidgets='1' name='Header Menu' showaddelement='no'>
                  <b:widget id='LinkList200' locked='true' title='' type='LinkList' visible='true'>
                    <b:widget-settings>
                      <b:widget-setting name='link-5'>{getPosts} $label={التكنولوجيا}</b:widget-setting>
                      <b:widget-setting name='link-6'>{getPosts} $label={الصحة}</b:widget-setting>
                      <b:widget-setting name='link-3'>{getPosts} $label={الميدان}</b:widget-setting>
                      <b:widget-setting name='link-4'>{getPosts} $label={متفرقات}</b:widget-setting>
                      <b:widget-setting name='text-1'>الثقافة</b:widget-setting>
                      <b:widget-setting name='text-0'>السياسة </b:widget-setting>
                      <b:widget-setting name='text-3'>الميدان </b:widget-setting>
                      <b:widget-setting name='text-2'>الرياضة </b:widget-setting>
                      <b:widget-setting name='text-5'>التكنولوجيا </b:widget-setting>
                      <b:widget-setting name='text-4'>متفرقات </b:widget-setting>
                      <b:widget-setting name='text-6'>الصحة </b:widget-setting>
                      <b:widget-setting name='sorting'>NONE</b:widget-setting>
                      <b:widget-setting name='link-1'>{getPosts} $label={الثقافة}</b:widget-setting>
                      <b:widget-setting name='link-2'>{getPosts} $label={الرياضة}</b:widget-setting>
                      <b:widget-setting name='link-0'>{getPosts} $label={السياسة}</b:widget-setting>
                    </b:widget-settings>
                    <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
                    <b:includable id='content'>
      <b:include name='linklist-content'/>
    </b:includable>
                  </b:widget>
                </b:section>
              </div>
              <div class='flex-right'>
                <div class='toggle-wrap'>
                  <b:tag aria-label='Dark Mode' class='darkmode-toggle' cond='data:skin.vars.darkmode == &quot;0px&quot; and (data:skin.vars.userdarkmode == &quot;1px&quot;)' name='button'/>
                  <b:tag class='search-toggle show-search btn' expr:aria-label='data:messages.search' name='button'/>
                </div>
              </div>
              <div id='main-search-wrap'>
                <div class='main-search'>
                  <form class='search-form' expr:action='data:blog.searchUrl'>
                    <b:attr cond='!data:view.isPreview' name='target' value='_top'/>
                    <input autocomplete='off' class='search-input' expr:aria-label='data:messages.search' expr:placeholder='data:messages.search' name='q' type='search' value=''/>
                    <button class='search-toggle search-close btn' type='reset'/>
                  </form>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <b:if cond='data:view.isLayoutMode or (data:view.isHomepage or (data:view.isPost and (data:skin.vars.ticker_onpost == &quot;1px&quot;))) and (data:widgets any w =&gt; w.sectionId == &quot;ticker&quot;)'>
      <div class='flex-c' id='ticker-wrapper'>
        <b:class cond='data:skin.vars.ticker_border == &quot;1px&quot;' name='has-border'/>
        <b:section class='ticker container row-x1' id='ticker' maxwidgets='1' name='Ticker News' showaddelement='yes'>
          <b:widget id='PopularPosts3' locked='false' title='العاجل' type='PopularPosts' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='numItemsToShow'>5</b:widget-setting>
              <b:widget-setting name='showThumbnails'>true</b:widget-setting>
              <b:widget-setting name='showSnippets'>true</b:widget-setting>
              <b:widget-setting name='timeRange'>ALL_TIME</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <div class='widget-content'>
        <b:if cond='data:widget.sectionId == &quot;ticker&quot;'>
          <div class='pbt-ticker ticker-items'>
            <b:loop index='i' values='data:posts' var='post'>
              <b:include data='post' name='content'/>
            </b:loop>
          </div>
        <b:elseif cond='data:widget.sectionId == &quot;trending&quot;'/>
          <div class='trending-items'>
            <b:loop index='i' values='data:posts' var='post'>
              <b:include cond='data:i lt 4' data='post' name='content'/>
            </b:loop>
          </div>
          <b:else/>
          <b:class name='side-items'/>
          <b:loop index='i' values='data:posts' var='post'>
            <b:include data='post' name='content'/>
          </b:loop>
        </b:if>
      </div>
    </b:includable>
            <b:includable id='blogThisShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='bylineByName' var='byline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='bylineRegion' var='regionItems'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentsLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentsLinkIframe'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='content' var='post'>
      <b:include name='popular-content'/>
    </b:includable>
            <b:includable id='emailPostIcon'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='facebookShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='footerBylines'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='googlePlusShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='headerByline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='linkShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='otherSharingButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='platformShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postAuthor'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postCommentsLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postJumpLink' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postLabels'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postLocation'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postReactions'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postShareButtons'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postTimestamp'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtonContent'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtons'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtonsMenu'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingPlatformIcon'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostByline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostContent'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostThumbnail'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostTitle'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPosts'><b:comment>Replaced</b:comment></b:includable>
          </b:widget>
        </b:section>
      </div>
    </b:if>
  </header>
  <b:if cond='data:view.isLayoutMode or (data:view.isHomepage and (data:widgets any w =&gt; w.sectionId == &quot;trending&quot;))'>
    <div class='flex-c' id='trending-wrapper'>
      <b:section class='trending container row-x1' id='trending' maxwidgets='1' name='Trending Posts' showaddelement='yes'>
        <b:widget id='HTML1' locked='false' title='ADS header on home page' type='HTML' visible='true'>
          <b:widget-settings>
            <b:widget-setting name='content'>{getPosts} $results={6} $label={recent}</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>
      <b:include name='html-content'/>
    </b:includable>
        </b:widget>
      </b:section>
    </div>
  </b:if>
  <div class='flex-c' id='content-wrapper'>
    <div class='container row-x1 flex-sb'>
      <main id='main-wrapper'>
        <b:section class='home-ads' cond='data:view.isHomepage and (data:widgets any w =&gt; w.sectionId == &quot;home-ads-1&quot;)' id='home-ads-1' maxwidgets='1' name='Home ADS 1' showaddelement='yes'/>
        <b:section class='featured' cond='data:view.isHomepage and (data:widgets.FeaturedPost any w =&gt; w.sectionId == &quot;featured&quot;)' id='featured' maxwidgets='1' name='Featured Post' showaddelement='yes'>
          <b:widget id='FeaturedPost1' locked='false' title='اختيار المحررين' type='FeaturedPost' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='showSnippet'>true</b:widget-setting>
              <b:widget-setting name='showPostTitle'>true</b:widget-setting>
              <b:widget-setting name='postId'>556676186055365741</b:widget-setting>
              <b:widget-setting name='showFirstImage'>true</b:widget-setting>
              <b:widget-setting name='useMostRecentPost'>false</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <div class='widget-content'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='content'/>
        </b:loop>
      </div>
    </b:includable>
            <b:includable id='blogThisShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='bylineByName' var='byline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='bylineRegion' var='regionItems'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentsLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentsLinkIframe'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='content' var='post'>
      <b:include name='featured-content'/>
    </b:includable>
            <b:includable id='emailPostIcon'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='facebookShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='footerBylines'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='googlePlusShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='headerByline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='linkShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='otherSharingButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='platformShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postAuthor'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postCommentsLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postJumpLink' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postLabels'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postLocation'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postReactions'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postShareButtons'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postTimestamp'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtonContent'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtons'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtonsMenu'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingPlatformIcon'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostByline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostContent'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostThumbnail'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostTitle'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPosts'><b:comment>Replaced</b:comment></b:includable>
          </b:widget>
        </b:section>
        <b:section class='home-ads' cond='data:view.isHomepage and (data:widgets any w =&gt; w.sectionId == &quot;home-ads-2&quot;)' id='home-ads-2' maxwidgets='1' name='Home ADS 2' showaddelement='yes'/>
        <b:section class='main' id='main' maxwidgets='1' name='Main Posts' showaddelement='yes'>
          <b:widget id='Blog1' locked='true' title='رسائل المدونة الإلكترونية' type='Blog' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='commentLabel'>$type={blogger}</b:widget-setting>
              <b:widget-setting name='showShareButtons'>true</b:widget-setting>
              <b:widget-setting name='authorLabel'>بواسطة</b:widget-setting>
              <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
              <b:widget-setting name='timestampLabel'>-</b:widget-setting>
              <b:widget-setting name='reactionsLabel'/>
              <b:widget-setting name='showAuthorProfile'>true</b:widget-setting>
              <b:widget-setting name='style.layout'>1x1</b:widget-setting>
              <b:widget-setting name='showLocation'>false</b:widget-setting>
              <b:widget-setting name='showTimestamp'>true</b:widget-setting>
              <b:widget-setting name='postsPerAd'>1</b:widget-setting>
              <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
              <b:widget-setting name='showDateHeader'>false</b:widget-setting>
              <b:widget-setting name='style.textcolor'>#ffffff</b:widget-setting>
              <b:widget-setting name='showCommentLink'>true</b:widget-setting>
              <b:widget-setting name='style.urlcolor'>#ffffff</b:widget-setting>
              <b:widget-setting name='postLocationLabel'>Location:</b:widget-setting>
              <b:widget-setting name='showAuthor'>true</b:widget-setting>
              <b:widget-setting name='style.linkcolor'>#ffffff</b:widget-setting>
              <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
              <b:widget-setting name='showLabels'>true</b:widget-setting>
              <b:widget-setting name='postLabelsLabel'>التسميات</b:widget-setting>
              <b:widget-setting name='showBacklinks'>false</b:widget-setting>
              <b:widget-setting name='showInlineAds'>false</b:widget-setting>
              <b:widget-setting name='showReactions'>false</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:class cond='data:view.isMultipleItems' name='index-blog flex-col'/>
      <b:include cond='data:view.isHomepage' name='blogPostsTitle'/>
      <b:include name='searchMessage'/>
      <b:if cond='!data:posts.empty'>
        <div class='blog-posts'>
          <b:class cond='data:view.isMultipleItems' expr:name='data:skin.vars.gridstyle == &quot;1px&quot; ? &quot;index-post-wrap grid-items&quot; : &quot;index-post-wrap list-items&quot;'/>
          <b:class cond='data:view.isSingleItem' name='item-post-wrap flex-col'/>
          <b:loop index='i' values='data:posts' var='post'>
            <b:include data='post' name='postCommentsAndAd'/>
          </b:loop>
        </div>
        <b:include cond='data:view.isMultipleItems' name='ajaxPagination'/>
      </b:if>
      <b:include name='feedLinks'/>
    </b:includable>
            <b:includable id='aboutPostAuthor'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='addComments'>
      <a expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'><data:messages.postAComment/></a>
    </b:includable>
            <b:includable id='ajaxPagination'>
      <!-- Ajax Pagination on Index -->
      <div class='blog-pager' id='blog-pager'>
        <b:if cond='data:olderPageUrl'>
          <a class='blog-pager-older-link load-more btn' expr:data-load='data:olderPageUrl.canonical' href='#' id='buzzspot-pro-load-more-link'><b:include data='{ message: &quot;loadMorePosts&quot; }' name='theme-custom-lang'/></a>
          <span class='loading'><div class='loader'/></span>
          <span class='no-more load-more btn'><data:messages.noResultsFound/></span>
          <b:else/>
          <span class='no-more load-more btn show'><data:messages.noResultsFound/></span>
        </b:if>
      </div>
    </b:includable>
            <b:includable id='backLinks' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='blogPostsTitle'>
      <b:if cond='data:blog.jumpLinkMessage != &quot;{hide}&quot;'>
        <div class='main-title-wrap blog1-title'><h3 class='title'><data:blog.jumpLinkMessage/></h3><a class='title-link' href='/search'><data:messages.viewAll/></a></div>
      </b:if>
    </b:includable>
            <b:includable id='blogThisShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='bylineByName' var='byline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='bylineRegion' var='regionItems'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentAuthorAvatar'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentDeleteIcon' var='comment'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentForm' var='post'>
      <div class='comment-form'>
        <a name='comment-form'/>
        <b:include data='post' name='commentFormIframeSrc'/>
        <iframe allowtransparency='allowtransparency' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='90px' id='comment-editor' name='comment-editor' src='' width='100%'/>
        <data:post.cmtfpIframe/>
        <script type='text/javascript'>
          BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
        </script>
      </div>
    </b:includable>
            <b:includable id='commentFormIframeSrc' var='post'>
      <a expr:href='data:post.commentFormIframeSrc + &quot;&amp;skin=soho&quot;' id='comment-editor-src' rel='noopener noreferrer' title='Comment Form Link'/>
    </b:includable>
            <b:includable id='commentItem' var='comment'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentList' var='comments'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentPicker' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='comments' var='post'>
      <a name='comments'/>
      <section class='comments threaded flex-col' expr:data-embed='data:post.embedCommentForm' expr:data-num-comments='data:post.numberOfComments' id='comments'>
        <b:class expr:name='data:post.numberOfComments != 0 ? &quot;has-comments&quot; : &quot;no-comments&quot;'/>
        <b:include name='commentsTitle'/>
        <b:if cond='data:post.allowNewComments'>
          <b:if cond='data:this.messages.blogComment'><p class='comments-message excerpt'><data:this.messages.blogComment/></p></b:if>
          <b:else/>
          <b:if cond='data:post.noNewCommentsText and (data:post.numberOfComments == 0)'><p class='comments-message no-new-comments excerpt'><data:post.noNewCommentsText/><em>*</em></p></b:if>
        </b:if>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.numberOfComments != 0'>
            <div class='comments-content'>
              <div id='comment-holder'>
                <data:post.commentHtml/>
              </div>
            </div>
          </b:if>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='commentForm'/>
          </b:if>
          <b:if cond='!data:post.allowNewComments'><b:if cond='data:post.noNewCommentsText and (data:post.numberOfComments != 0)'><p class='comments-message no-new-comments excerpt'><data:post.noNewCommentsText/><em>*</em></p></b:if></b:if>
          <b:else/>
          <p class='comments-message excerpt'>Please Select Embedded Mode To Show The Comment System.<em>*</em></p>
        </b:if>
      </section>
    </b:includable>
            <b:includable id='commentsLink'>
  <a class='comment-link' expr:href='data:post.commentsUrl' expr:onclick='data:post.commentsUrlOnclick'>
    <b:if cond='data:post.numberOfComments &gt; 0'>
      <b:message name='messages.numberOfComments'>
        <b:param expr:value='data:post.numberOfComments' name='numComments'/>
      </b:message>
    <b:else/>
      <data:messages.postAComment/>
    </b:if>
  </a>
</b:includable>
            <b:includable id='commentsLinkIframe'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
            <b:includable id='commentsTitle'>
      <!-- Comments Title -->
      <div class='main-title-wrap comments-title'><b:class expr:name='data:this.messages.blogComment ? &quot;has-message&quot; : &quot;no-message&quot;'/><h3 class='title'><b:if cond='data:post.numberOfComments != 0'><b:if cond='data:allBylineItems.comments.label contains &quot;disqus&quot; or data:allBylineItems.comments.label contains &quot;facebook&quot;'><data:messages.postAComment/><b:else/><data:post.numberOfComments/> <data:messages.comments/></b:if><b:else/><data:messages.postAComment/></b:if></h3></div>
    </b:includable>
            <b:includable id='defaultAdUnit'>
      <ins class='adsbygoogle' data-ad-format='fluid' data-full-width-responsive='false' expr:data-ad-client='data:adClientId ?: data:blog.adsenseClientId' expr:data-ad-host='data:blog.adsenseHostId' expr:data-ad-layout-key='data:skin.vars.gridstyle != &quot;1px&quot; ? &quot;-fk-2c+dv+k-18j&quot; : &quot;-6n+e2+3n-6a+2e&quot;' expr:data-analytics-uacct='data:blog.analyticsAccountNumber' style='display:block'/>
      <script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
    </b:includable>
            <b:includable id='emailPostIcon'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='facebookShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='feedLinks'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='feedLinksBody' var='links'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='footerBylines'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='googlePlusShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='headerByline' var='post'>
      <!-- Post Entry Meta -->
      <b:if cond='data:view.isMultipleItems'>
        <b:if cond='data:allBylineItems.author or data:allBylineItems.timestamp'>
          <div class='entry-meta'>
            <b:class cond='data:skin.vars.gridstyle == &quot;1px&quot; and (data:skin.vars.summary == &quot;1px&quot;)' name='has-snip'/>
            <b:include cond='data:allBylineItems.author' data='post' name='postAuthor'/>
            <b:include cond='data:allBylineItems.timestamp' data='post' name='postTimestamp'/>
          </div>
        </b:if>
      </b:if>
      <b:if cond='data:view.isPost'>
        <b:if cond='data:allBylineItems.author or data:allBylineItems.timestamp or data:allBylineItems.share'>
          <b:class name='has-meta'/>
          <div class='entry-meta'>
            <div class='align-left'>
              <b:class cond='data:allBylineItems.timestamp' name='has-time'/>
              <b:if cond='data:allBylineItems.author'><span class='entry-avatar'><span class='avatar' expr:data-src='data:post.author.authorPhoto.image ? resizeImage(data:post.author.authorPhoto.image, 72, &quot;1:1&quot;) : &quot;https://1.bp.blogspot.com/-QN2lgvtYZco/YN3mUSryAVI/AAAAAAAAADs/KrR-etCcvUMcPl06jopTs9pzq59IAXhMQCLcBGAsYHQ/s72-c/avatar.jpg&quot;'/></span></b:if>
              <b:tag class='al-items' cond='data:allBylineItems.author and data:allBylineItems.timestamp' name='div'>
              <b:include cond='data:allBylineItems.author' data='post' name='postAuthor'/>
              <b:include cond='data:allBylineItems.timestamp' data='post' name='postTimestamp'/>
              </b:tag>
            </div>
            <b:if cond='data:allBylineItems.share'>
              <div class='align-right'>
                <button class='share-toggle btn' expr:aria-label='data:messages.share'/>
              </div>
            </b:if>
          </div>
        </b:if>
      </b:if>
    </b:includable>
            <b:includable id='homePageLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='iframeComments' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='indexPost' var='post'>
      <!-- Index Post Content -->
      <b:include data='post' name='postFeaturedImage'/>
      <div class='entry-header'>
        <b:include cond='data:skin.vars.entrytag == &quot;1px&quot; and (data:skin.vars.gridstyle != &quot;1px&quot;)' data='post' name='postCategory'/>
        <b:include data='post' name='postHeader'/>
        <b:include cond='data:skin.vars.summary == &quot;1px&quot;' data='post' name='postBodySnippet'/>
        <b:include data='post' name='headerByline'/>
      </div>
    </b:includable>
            <b:includable id='inlineAd' var='post'>
      <b:if cond='!data:view.isPreview'>
        <b:if cond='data:i != 0'>
          <b:if cond='data:post.includeAd and data:post.adNumber'>
            <b:if cond='data:this.adCode or data:this.adClientId or data:blog.adsenseClientId'>
              <div class='post ad-type'>
                <div class='inline-ad-wrap'>
                  <div class='inline-ad'>
                    <b:if cond='data:this.adCode != &quot;&quot;'>
                      <data:this.adCode/>
                      <b:else/>
                      <b:if cond='data:this.adClientId or data:blog.adsenseClientId'>
                        <b:include name='defaultAdUnit'/>
                      </b:if>
                    </b:if>
                  </div>
                </div>
              </div>
            </b:if>
          </b:if>
        </b:if>
      </b:if>
    </b:includable>
            <b:includable id='itemPost' var='post'>
      <!-- Item Post Content -->
      <b:include data='post' name='postMeta'/>
      <div class='item-post-inner flex-col'>
        <div class='entry-header p-eh'>
          <b:include data='post' name='postHeader'/>
        </div>
        <div class='entry-content-wrap flex-col'>
          <b:include data='post' name='postBody'/>
          <b:include cond='data:view.isPost and data:allBylineItems.labels' data='post' name='postLabels'/>
        </div>
        <b:include cond='data:view.isPost and data:allBylineItems.share' data='post' name='postShareButtons'/>
      </div>
      <b:include cond='data:view.isPost' data='post' name='postFooter'/>
    </b:includable>
            <b:includable id='linkShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='nextPageLink'>
      <b:if cond='data:olderPageUrl'>
        <a class='post-nav-link post-nav-older-link' expr:href='data:olderPageUrl.canonical'>
          <b:include data='{ message: &quot;nextPost&quot; }' name='theme-custom-lang'/>
        </a>
        <b:else/>
        <span class='post-nav-link post-nav-older-link'>
          <b:include data='{ message: &quot;nextPost&quot; }' name='theme-custom-lang'/>
        </span>
      </b:if>
    </b:includable>
            <b:includable id='otherSharingButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='platformShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='post' var='post'>
      <!-- Index Posts -->
      <b:if cond='data:view.isMultipleItems'>
        <b:include data='post' name='indexPost'/>
      </b:if>
      <!-- Item Post -->
      <b:if cond='data:view.isSingleItem'>
        <b:include data='post' name='itemPost'/>
      </b:if>
    </b:includable>
            <b:includable id='postAuthor' var='post'>
      <!-- Post Author -->
      <span class='entry-author mi'><b:if cond='data:allBylineItems.author.label'><span class='by sp'><data:allBylineItems.author.label/></span></b:if><span class='author-name'><data:post.author.name/></span></span>
    </b:includable>
            <b:includable id='postBody' var='post'> 
      <!-- Ads before post content. -->
      <b:if cond='data:view.isPost'><b:tag cond='data:widgets any w =&gt; w.sectionId == &quot;buzzspot-pro-main-before-ad&quot;' id='before-ad' name='div'/></b:if>
      <!-- Post Body Entry Content-->
      <div class='post-body entry-content' id='post-body'>
        <data:post.body/>
      </div>
      <!-- Ads after post content. -->
      <b:if cond='data:view.isPost'><b:tag cond='data:widgets any w =&gt; w.sectionId == &quot;buzzspot-pro-main-after-ad&quot;' id='after-ad' name='div'/></b:if>
    </b:includable>
            <b:includable id='postBodySnippet' var='post'><p class='entry-excerpt excerpt'><b:eval expr='data:post.snippets.long snippet { length: 88 }'/></p></b:includable>
            <b:includable id='postBreadcrumbs' var='post'>
      <!-- Post Breadcrumbs -->
      <b:if cond='data:view.isPost'>
        <b:if cond='data:skin.vars.breadcrumb == &quot;1px&quot;'><nav id='breadcrumb'><a class='home' expr:href='data:blog.homepageUrl'><data:messages.home/></a><b:if cond='data:post.labels'><em class='separator'/><a class='label' expr:href='data:post.labels.first.url'><data:post.labels.first.name/></a></b:if></nav></b:if>
        <script type='application/ld+json'>{&quot;@context&quot;:&quot;http://schema.org&quot;,&quot;@type&quot;:&quot;BreadcrumbList&quot;,&quot;itemListElement&quot;:[{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:1,&quot;name&quot;:&quot;<data:messages.home.jsonEscaped/>&quot;,&quot;item&quot;:&quot;<data:blog.homepageUrl.canonical.jsonEscaped/>&quot;},{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:2,&quot;name&quot;:&quot;<b:if cond='data:post.labels'><data:post.labels.first.name.jsonEscaped/><b:else/><data:messages.posts/></b:if>&quot;,&quot;item&quot;:&quot;<b:if cond='data:post.labels'><data:post.labels.first.url.canonical.jsonEscaped/><b:else/><b:eval expr='data:blog.homepageUrl.canonical.jsonEscaped + &quot;search/&quot;'/></b:if>&quot;},{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:3,&quot;name&quot;:&quot;<data:post.title.jsonEscaped/>&quot;,&quot;item&quot;:&quot;<data:post.url.canonical.jsonEscaped/>&quot;}]}</script>
      </b:if>
      <b:if cond='data:view.isPage'>
        <script type='application/ld+json'>{&quot;@context&quot;:&quot;http://schema.org&quot;,&quot;@type&quot;:&quot;BreadcrumbList&quot;,&quot;itemListElement&quot;:[{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:1,&quot;name&quot;:&quot;<data:messages.home.jsonEscaped/>&quot;,&quot;item&quot;:&quot;<data:blog.homepageUrl.canonical.jsonEscaped/>&quot;},{&quot;@type&quot;:&quot;ListItem&quot;,&quot;position&quot;:2,&quot;name&quot;:&quot;<data:post.title.jsonEscaped/>&quot;,&quot;item&quot;:&quot;<data:post.url.canonical.jsonEscaped/>&quot;}]}</script>
      </b:if>
    </b:includable>
            <b:includable id='postCategory' var='post'>
      <!-- Post Label -->
      <b:if cond='data:post.labels'><span class='entry-category'><data:post.labels.first.name/></span></b:if>
    </b:includable>
            <b:includable id='postCommentsAndAd' var='post'>
      <!-- In-Feed Ads -->
      <b:include cond='data:view.isMultipleItems and not data:view.search.label and not data:view.search.query and not data:view.isArchive' data='post' name='inlineAd'/>
      <article>
        <b:class cond='data:view.isMultipleItems' expr:name='data:skin.vars.gridstyle == &quot;1px&quot; ? &quot;post hentry item-&quot; + data:i : &quot;post hentry item-&quot; + data:i'/>
        <b:class cond='data:view.isSingleItem' name='item-post hentry flex-col'/>
        <b:include data='post' name='post'/>
      </article>
      <b:if cond='data:view.isSingleItem and data:post.allowComments'>
        <!-- Post Comments -->
        <div class='buzzspot-pro-blog-post-comments post-widget' expr:data-shortcode='data:allBylineItems.comments.label contains &quot;type&quot; ? data:allBylineItems.comments.label : &quot;$type={blogger}&quot;'>
          <b:include data='post' name='threadedCommentsDisqus'/>
          <b:include data='post' name='comments'/>
        </div>
      </b:if>
      <!-- Post Navigation -->
      <b:include cond='data:skin.vars.postnav == &quot;1px&quot;' name='postPagination'/>
    </b:includable>
            <b:includable id='postCommentsLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postFeaturedImage' var='post'>
      <!-- Post Featured Image -->
      <a class='entry-thumbnail' expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle'><b:if cond='data:post.featuredImage'><span class='thumbnail' expr:data-src='data:post.featuredImage.isYouTube ? resizeImage(data:post.featuredImage.youtubeMaxResDefaultUrl.jsonEscaped, 72, &quot;1:1&quot;) : resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)'/><b:else/><span class='thumbnail' data-src='https://resources.blogblog.com/img/blank.gif'/></b:if><b:class cond='data:post.featuredImage.isYouTube' name='is-ytimg'/><b:include cond='data:skin.vars.thumbtag == &quot;1px&quot; and (data:skin.vars.gridstyle == &quot;1px&quot;)' data='post' name='postCategory'/></a>
    </b:includable>
            <b:includable id='postFooter' var='post'>
      <!-- Post Footer Items -->
      <b:tag class='post-footer flex-col' cond='data:post.author.aboutMe or (data:widgets.HTML any w =&gt; w.sectionId == &quot;buzzspot-pro-related-posts&quot;) or (data:widgets any w =&gt; w.sectionId == &quot;buzzspot-pro-post-footer-ads&quot;)' name='footer'>
        <b:include cond='data:post.author.aboutMe' data='post' name='postFooterAuthorProfile'/>
        <b:include cond='data:widgets.HTML any w =&gt; w.sectionId == &quot;buzzspot-pro-related-posts&quot;' data='post' name='relatedPosts'/>
        <b:tag class='post-widget' cond='data:widgets any w =&gt; w.sectionId == &quot;buzzspot-pro-post-footer-ads&quot;' id='post-footer-ads' name='div'/>
      </b:tag>
    </b:includable>
            <b:includable id='postFooterAuthorProfile' var='post'>
      <div class='about-author post-widget'>
        <div class='author-avatar entry-avatar'>
          <span class='avatar' expr:data-src='data:post.author.authorPhoto.image ? resizeImage(data:post.author.authorPhoto.image, 72, &quot;1:1&quot;) : &quot;https://1.bp.blogspot.com/-QN2lgvtYZco/YN3mUSryAVI/AAAAAAAAADs/KrR-etCcvUMcPl06jopTs9pzq59IAXhMQCLcBGAsYHQ/s72-c/avatar.jpg&quot;'/>
        </div>
        <div class='author-description flex-col'>
          <h3 class='author-title'><b:tag cond='data:post.author.profileUrl' expr:alt='data:post.author.name' expr:href='data:post.author.profileUrl' name='a' rel='noopener noreferrer' target='_blank'><data:post.author.name/></b:tag></h3>
          <p class='author-text excerpt'><data:post.author.aboutMe/></p>
        </div>
      </div>
    </b:includable>
            <b:includable id='postHeader' var='post'>
      <b:include cond='data:view.isSingleItem' data='post' name='postBreadcrumbs'/>
      <b:include data='post' name='postTitle'/>
      <b:include cond='data:view.isPost' data='post' name='headerByline'/>
    </b:includable>
            <b:includable id='postJumpLink' var='post'>
      <b:if cond='data:blog.jumpLinkMessage != &quot;hide&quot;'>
        <a class='read-more' expr:href='data:post.url.canonical'><data:blog.jumpLinkMessage/></a>
      </b:if>
    </b:includable>
            <b:includable id='postLabels' var='post'>
      <b:if cond='data:post.labels'>
        <div class='entry-labels'>
          <b:if cond='data:allBylineItems.labels.label'><span class='labels-label btn'><data:allBylineItems.labels.label/></span></b:if>
          <b:loop values='data:post.labels' var='label'>
            <a class='label-link btn' expr:href='data:label.url' rel='tag'><data:label.name/></a>
          </b:loop>
        </div>
      </b:if>
    </b:includable>
            <b:includable id='postLocation'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postMeta' var='post'>
      <b:if cond='data:view.isPost'>
        <script type='application/ld+json'>{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;NewsArticle&quot;,&quot;mainEntityOfPage&quot;:{&quot;@type&quot;:&quot;WebPage&quot;,&quot;@id&quot;:&quot;<data:post.url.canonical.jsonEscaped/>&quot;},&quot;headline&quot;:&quot;<data:post.title.jsonEscaped/>&quot;,&quot;description&quot;:&quot;<data:post.snippets.short.jsonEscaped/>&quot;,&quot;datePublished&quot;:&quot;<data:post.date.iso8601.jsonEscaped/>&quot;,&quot;dateModified&quot;:&quot;<data:post.lastUpdated.iso8601.jsonEscaped/>&quot;,&quot;image&quot;:{&quot;@type&quot;:&quot;ImageObject&quot;,<b:if cond='data:post.featuredImage.isResizable'>&quot;url&quot;:&quot;<b:eval expr='resizeImage(data:post.featuredImage, 1200, &quot;1200:675&quot;)'/>&quot;,&quot;height&quot;:675,&quot;width&quot;:1200<b:else/>&quot;url&quot;:&quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=w1200&quot;,&quot;height&quot;:348,&quot;width&quot;:1200</b:if>},&quot;author&quot;:{&quot;@type&quot;:&quot;Person&quot;,&quot;name&quot;:&quot;<data:post.author.name.jsonEscaped/>&quot;},&quot;publisher&quot;:{&quot;@type&quot;:&quot;Organization&quot;,&quot;name&quot;:&quot;Blogger&quot;,&quot;logo&quot;:{&quot;@type&quot;:&quot;ImageObject&quot;,&quot;url&quot;:&quot;https://lh3.googleusercontent.com/ULB6iBuCeTVvSjjjU1A-O8e9ZpVba6uvyhtiWRti_rBAs9yMYOFBujxriJRZ-A=h60&quot;,&quot;width&quot;:206,&quot;height&quot;:60}}}</script>
      </b:if>
    </b:includable>
            <b:includable id='postMetadataJSONImage'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postMetadataJSONPublisher'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postPagination'>
      <b:if cond='data:view.isPost'>
        <div class='post-nav post-widget'>
          <b:include name='previousPageLink'/>
          <b:include name='nextPageLink'/>
        </div>
      </b:if>
    </b:includable>
            <b:includable id='postReactions'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postShareButtons' var='post'>
      <!-- Post Share Buttons & Modal -->
      <div class='post-share'>
        <ul class='share-a social sb-a'>
          <li class='share-label'><span class='sl-btn btn'><i class='sl-ico'/></span></li>
          <li class='facebook has-span'><a class='fa-facebook btn pbt-window' data-height='500' data-width='520' expr:data-url='&quot;https://www.facebook.com/sharer.php?u=&quot; + data:post.url.canonical' href='#' rel='noopener noreferrer' title='Facebook'><span>Facebook</span></a></li>
          <li class='twitter has-span'><a class='fa-twitter btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://twitter.com/intent/tweet?url=&quot; + data:post.url.canonical + &quot;&amp;text=&quot; + data:post.title.jsEscaped' href='#' rel='noopener noreferrer' title='Twitter'><span>Twitter</span></a></li>
          <li class='whatsapp'><a class='fa-whatsapp btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://api.whatsapp.com/send?text=&quot; + data:post.title.jsEscaped + &quot; | &quot; + data:post.url.canonical' href='#' rel='noopener noreferrer' title='WhatsApp'/></li>
          <li class='email'><a class='fa-email btn pbt-window' data-height='500' data-width='520' expr:data-url='&quot;mailto:?subject=&quot; + data:post.title.jsEscaped + &quot;&amp;body=&quot; + data:post.url.canonical' href='#' rel='noopener noreferrer' title='Email'/></li>
          <li class='show-more'><button class='btn' expr:aria-label='data:messages.showMore'/></li>
        </ul>
        <div class='share-modal'>
          <div class='modal-inner'>
            <div class='modal-header'>
              <span class='modal-thumb entry-thumbnail'><b:if cond='data:post.featuredImage'><span class='thumbnail' expr:data-src='data:post.featuredImage.isYouTube ? resizeImage(data:post.featuredImage.youtubeMaxResDefaultUrl.jsonEscaped, 72, &quot;1:1&quot;) : resizeImage(data:post.featuredImage, 72, &quot;1:1&quot;)'/><b:else/><span class='entry-thumbnail' data-src='https://resources.blogblog.com/img/blank.gif'/></b:if><b:class cond='data:post.featuredImage.isYouTube' name='sz-5 is-ytimg'/></span>
              <span class='modal-title'><span class='strong'><data:messages.share/>:</span><span class='title'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></span></span>
            </div>
            <ul class='share-b social sb-a'>
              <li class='facebook'><a class='fa-facebook btn pbt-window' data-height='500' data-width='520' expr:data-url='&quot;https://www.facebook.com/sharer.php?u=&quot; + data:post.url.canonical' href='#' rel='noopener noreferrer' title='Facebook'><span>Facebook</span></a></li>
              <li class='twitter'><a class='fa-twitter btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://twitter.com/intent/tweet?url=&quot; + data:post.url.canonical + &quot;&amp;text=&quot; + data:post.title.jsEscaped' href='#' rel='noopener noreferrer' title='Twitter'><span>Twitter</span></a></li>
              <li class='whatsapp'><a class='fa-whatsapp btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://api.whatsapp.com/send?text=&quot; + data:post.title.jsEscaped + &quot; | &quot; + data:post.url.canonical' href='#' rel='noopener noreferrer' title='WhatsApp'><span>WhatsApp</span></a></li>
              <li class='pinterest-p'><a class='fa-pinterest-p btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://www.pinterest.com/pin/create/button/?url=&quot; + data:post.url.canonical + &quot;&amp;media=&quot; + data:post.featuredImage + &quot;&amp;description=&quot; + data:post.title.jsEscaped' href='#' rel='noopener noreferrer' title='Pinterest'><span>Pinterest</span></a></li>
              <li class='linkedin'><a class='fa-linkedin-in btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://www.linkedin.com/shareArticle?mini=true&amp;url=&quot; + data:post.url.canonical + &quot;&amp;title=&quot; + data:post.title.jsEscaped' href='#' rel='noopener noreferrer' title='LinkedIn'><span>LinkedIn</span></a></li>
              <li class='reddit'><a class='fa-reddit-alien btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://reddit.com/submit?url=&quot; + data:post.url.canonical + &quot;&amp;title=&quot; + data:post.title.jsEscaped' href='#' rel='noopener noreferrer' title='Reddit'><span>Reddit</span></a></li>
              <li class='tumblr'><a class='fa-tumblr btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://www.tumblr.com/share/link?url=&quot; + data:post.url.canonical + &quot;&amp;name=&quot; + data:post.title.jsEscaped' href='#' rel='noopener noreferrer' title='Tumblr'><span>Tumblr</span></a></li>
              <li class='telegram'><a class='fa-telegram-plane btn pbt-window' data-height='520' data-width='860' expr:data-url='&quot;https://telegram.me/share/url?url=&quot; + data:post.url.canonical + &quot;&amp;text=&quot; + data:post.title.jsEscaped' href='#' rel='noopener noreferrer' title='Telegram'><span>Telegram</span></a></li>
              <li class='email'><a class='fa-email btn pbt-window' data-height='500' data-width='520' expr:data-url='&quot;mailto:?subject=&quot; + data:post.title.jsEscaped + &quot;&amp;body=&quot; + data:post.url.canonical' href='#' rel='noopener noreferrer' title='Email'><span>Email</span></a></li>
            </ul>
          </div>
          <button class='hide-modal' expr:aria-label='data:messages.showLess'/>
        </div>
        <b:tag class='overlay' id='share-overlay' name='div'/>
      </div>
    </b:includable>
            <b:includable id='postTimestamp' var='post'>
      <!-- Post Timestamp -->
      <span class='entry-time mi'><b:if cond='data:allBylineItems.author and data:allBylineItems.timestamp.label'><span class='sp'><data:allBylineItems.timestamp.label/></span></b:if><time class='published' expr:datetime='data:post.date.iso8601'><data:post.date/></time></span>
    </b:includable>
            <b:includable id='postTitle' var='post'>
      <!-- Post Title Index and Item -->
      <b:if cond='data:view.isMultipleItems'>
        <h2 class='entry-title'><a expr:href='data:post.url.canonical' expr:title='data:post.title ? data:post.title : data:messages.noTitle' rel='bookmark'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></a></h2>
      </b:if>
      <b:if cond='data:view.isSingleItem'>
        <h1 class='entry-title'><b:eval expr='data:post.title ? data:post.title : data:messages.noTitle'/></h1>
      </b:if>
    </b:includable>
            <b:includable id='previousPageLink'>
      <b:if cond='data:newerPageUrl'>
        <a class='post-nav-link post-nav-newer-link' expr:href='data:newerPageUrl.canonical'>
          <b:include data='{ message: &quot;prevPost&quot; }' name='theme-custom-lang'/>
        </a>
        <b:else/>
        <span class='post-nav-link post-nav-newer-link'>
          <b:include data='{ message: &quot;prevPost&quot; }' name='theme-custom-lang'/>
        </span>
      </b:if>
    </b:includable>
            <b:includable id='relatedPosts' var='post'>
      <!-- Related Posts -->
      <div class='post-widget' id='related-wrap'>
        <div class='main-title-wrap related-title'>
          <b:with value='data:widgets.HTML filter (w =&gt; w.sectionId == &quot;buzzspot-pro-related-posts&quot;) map (w =&gt; w.title)' var='pbtTitle'>
            <h3 class='title'><b:eval expr='data:pbtTitle.first ? data:pbtTitle.first : data:messages.youMayLikeThesePosts'/></h3>
          </b:with>
          <a class='title-link' expr:href='data:post.labels ? data:post.labels.first.url : &quot;/search&quot;'><data:messages.viewAll/></a>
        </div>
        <div class='related-content'>
          <b:if cond='data:post.labels'>
            <div class='related-tag' expr:data-id='data:post.id' expr:data-label='data:post.labels.first.name'/>
            <b:else/>
            <div class='related-tag' data-label='recent' expr:data-id='data:post.id'/>
          </b:if>
        </div> 
      </div>  
    </b:includable>
            <b:includable id='searchMessage'>
      <!-- Search Message -->
      <b:if cond='data:posts.empty'>
        <b:class name='no-posts'/>
      </b:if>
      <b:if cond='data:view.search.query'>
        <div class='queryMessage'>
          <b:if cond='data:posts.empty'>
            <span class='query-info query-error'>&quot;<data:view.search.query/>&quot;</span>
            <b:else/>
            <span class='query-info query-success'>&quot;<data:view.search.query/>&quot;</span>
          </b:if>
        </div>
      </b:if>
      <b:if cond='data:view.search.label'>
        <div class='queryMessage '>
          <b:if cond='data:posts.empty'>
            <span class='query-info query-label query-error'><data:view.search.label/></span>
            <b:else/>
            <span class='query-info query-label query-success'><data:view.search.label/></span>
          </b:if>
        </div>
      </b:if>
      <b:if cond='data:view.isArchive'>
        <div class='queryMessage'>
          <b:if cond='data:posts.empty'>
            <span class='query-info query-error'><data:view.archive.rangeMessage/></span>
            <b:else/>
            <span class='query-info query-success'><data:view.archive.rangeMessage/></span>
          </b:if>
        </div>
      </b:if>
      <b:if cond='data:view.isError'>
        <div class='errorWrap'>
          <h3>404</h3>
          <h4><data:messages.theresNothingHere/></h4>
          <p><data:navMessage/></p>
          <a class='homepage btn' expr:href='data:blog.homepageUrl'><data:messages.home/></a>
        </div>
      </b:if>
      <b:if cond='data:view.isMultipleItems and data:posts.empty'><div class='queryEmpty'><data:messages.noResultsFound/></div></b:if>
    </b:includable>
            <b:includable id='sharingButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtonContent'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtons'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtonsMenu'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingPlatformIcon'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='threadedCommentForm' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='threadedCommentJs' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='threadedComments' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='threadedCommentsDisqus' var='post'>
      <script type='text/javascript'>
        var disqus_shortname = &quot;probloggertemplates&quot;;
        var disqus_blogger_current_url = &quot;<data:post.url.canonical/>&quot;;
        if (!disqus_blogger_current_url.length) {
          disqus_blogger_current_url = &quot;<data:post.url.canonical/>&quot;;
        }
        var disqus_blogger_homepage_url = &quot;<data:blog.canonicalHomepageUrl/>&quot;;
        var disqus_blogger_canonical_homepage_url = &quot;<data:blog.canonicalHomepageUrl/>&quot;;
      </script>
    </b:includable>
          </b:widget>
          <b:widget cond='data:view.isPost AND data:blog.isMobileRequest AND !data:view.isPreview' id='HTML10' locked='false' title='Parallax Ads (mobile post only)' type='HTML' version='2' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'/>
            </b:widget-settings>
            <b:includable id='main'><b:attr name='class' value='ignielParallax igniplexTengah'/><div class='prlx1 a'><div class='prlx2 fi f'><data:content/></div></div></b:includable>
            <b:includable id='widget-title'><b:comment>Don&#39;t show.</b:comment></b:includable>
          </b:widget>
          <b:widget cond='(!data:view.isSearch AND !data:view.isArchive) AND !data:view.isPreview' id='HTML7' locked='false' title='Ads Top' type='HTML' version='2' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'/>
            </b:widget-settings>
            <b:includable id='main'>
      <b:include name='html-content'/>
    </b:includable>
            <b:includable id='widget-title'><b:comment>Don&#39;t show.</b:comment></b:includable>
          </b:widget>
          <b:widget cond='data:view.isPost AND !data:blog.isMobileRequest AND !data:view.isPreview' id='HTML9' locked='false' title='Middle Ads (desktop post only)' type='HTML' version='2' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'/>
            </b:widget-settings>
            <b:includable id='main'><b:attr name='class' value='igniplexTengah'/><data:content/></b:includable>
            <b:includable id='widget-title'><b:comment>Don&#39;t show.</b:comment></b:includable>
          </b:widget>
        </b:section>
        <b:tag cond='data:view.isLayoutMode or (data:view.isPost and (data:widgets any w =&gt; w.sectionId in [&quot;buzzspot-pro-main-before-ad&quot;,&quot;buzzspot-pro-main-after-ad&quot;]))' id='custom-ads' name='div'>
          <b:section cond='data:view.isLayoutMode or (data:view.isPost and (data:widgets any w =&gt; w.sectionId == &quot;buzzspot-pro-main-before-ad&quot;))' id='buzzspot-pro-main-before-ad' maxwidgets='1' name='Post ADS 1' showaddelement='yes'/>
          <b:section cond='data:view.isLayoutMode or (data:view.isPost and (data:widgets any w =&gt; w.sectionId == &quot;buzzspot-pro-main-after-ad&quot;))' id='buzzspot-pro-main-after-ad' maxwidgets='1' name='Post ADS 2' showaddelement='yes'/>
        </b:tag>
        <b:section cond='data:view.isLayoutMode or (data:view.isPost and (data:widgets.HTML any w =&gt; w.sectionId == &quot;buzzspot-pro-related-posts&quot;))' id='buzzspot-pro-related-posts' maxwidgets='1' name='Related Posts' showaddelement='yes'>
          <b:widget id='HTML51' locked='true' title='قد ترغب' type='HTML' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='content'>{getPosts} $results={4}</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <b:include name='html-content'/>
    </b:includable>
          </b:widget>
        </b:section>
        <b:section cond='data:view.isLayoutMode or (data:view.isPost and (data:widgets any w =&gt; w.sectionId == &quot;buzzspot-pro-post-footer-ads&quot;))' id='buzzspot-pro-post-footer-ads' maxwidgets='1' name='Post ADS 3' showaddelement='yes'/>
      </main>
      <aside id='sidebar-wrapper'>
        <b:section class='sidebar pbt-section' cond='!data:view.isError' id='sidebar' name='Sidebar' showaddelement='yes'>
          <b:widget id='ContactForm2' locked='false' title='نموذج الاتصال' type='ContactForm' visible='true'>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
            <b:includable id='content'>
      <b:include name='contact-form-content'/>
    </b:includable>
          </b:widget>
          <b:widget id='LinkList1' locked='false' title='تابعنا' type='LinkList' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='text-8'>youtube</b:widget-setting>
              <b:widget-setting name='link-7'>https://twitter.com/ # 39k</b:widget-setting>
              <b:widget-setting name='link-8'>https://www.youtube.com/?sub_confirmation=1 # 65k</b:widget-setting>
              <b:widget-setting name='link-5'>https://www.quora.com #35k</b:widget-setting>
              <b:widget-setting name='link-6'>https://tiktok.com  #10k</b:widget-setting>
              <b:widget-setting name='link-3'>www.instgram.com # 23k</b:widget-setting>
              <b:widget-setting name='link-4'>https://www.pinterest.com  #20k</b:widget-setting>
              <b:widget-setting name='text-1'>facebook</b:widget-setting>
              <b:widget-setting name='text-0'>{getSocial}</b:widget-setting>
              <b:widget-setting name='text-3'>instagram</b:widget-setting>
              <b:widget-setting name='text-2'>github</b:widget-setting>
              <b:widget-setting name='text-5'>quora</b:widget-setting>
              <b:widget-setting name='text-4'>pinterest</b:widget-setting>
              <b:widget-setting name='text-7'>twitter</b:widget-setting>
              <b:widget-setting name='text-6'>tiktok </b:widget-setting>
              <b:widget-setting name='sorting'>ALPHABETICAL</b:widget-setting>
              <b:widget-setting name='link-1'>https://www.facebook.com/# 25k</b:widget-setting>
              <b:widget-setting name='link-2'>https://www.github.com #50k</b:widget-setting>
              <b:widget-setting name='link-0'>#</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
            <b:includable id='content'>
      <b:include name='linklist-content'/>
    </b:includable>
          </b:widget>
          <b:widget id='PopularPosts1' locked='false' title='منشورات شائعة' type='PopularPosts' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='numItemsToShow'>6</b:widget-setting>
              <b:widget-setting name='showThumbnails'>true</b:widget-setting>
              <b:widget-setting name='showSnippets'>true</b:widget-setting>
              <b:widget-setting name='timeRange'>LAST_YEAR</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <div class='widget-content'>
        <b:if cond='data:widget.sectionId == &quot;ticker&quot;'>
          <div class='pbt-ticker ticker-items'>
            <b:loop index='i' values='data:posts' var='post'>
              <b:include data='post' name='content'/>
            </b:loop>
          </div>
        <b:elseif cond='data:widget.sectionId == &quot;trending&quot;'/>
          <div class='trending-items'>
            <b:loop index='i' values='data:posts' var='post'>
              <b:include cond='data:i lt 4' data='post' name='content'/>
            </b:loop>
          </div>
          <b:else/>
          <b:class name='side-items'/>
          <b:loop index='i' values='data:posts' var='post'>
            <b:include data='post' name='content'/>
          </b:loop>
        </b:if>
      </div>
    </b:includable>
            <b:includable id='blogThisShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='bylineByName' var='byline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='bylineRegion' var='regionItems'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentsLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='commentsLinkIframe'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='content' var='post'>
      <b:include name='popular-content'/>
    </b:includable>
            <b:includable id='emailPostIcon'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='facebookShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='footerBylines'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='googlePlusShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='headerByline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='linkShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='otherSharingButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='platformShare'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postAuthor'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postCommentsLink'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postJumpLink' var='post'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postLabels'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postLocation'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postReactions'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postShareButtons'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='postTimestamp'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButton'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtonContent'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtons'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingButtonsMenu'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='sharingPlatformIcon'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostByline'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostContent'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostThumbnail'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPostTitle'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='snippetedPosts'><b:comment>Replaced</b:comment></b:includable>
          </b:widget>
          <b:widget id='HTML19' locked='false' title='{getMailchimp} $title={الايميل الخاص} $text={اشترك في قائمتنا البريدية للحصول على التحديثات الجدي.}' type='HTML' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[https://probloggertemplates.us6.list-manage.com/subscribe?u=98155398e3195ed8f58e2b86c&id=64e8605563]]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <b:include name='html-content'/>
    </b:includable>
          </b:widget>
          <b:widget id='HTML12' locked='false' title='آخر المشاركات' type='HTML' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='content'>{getPosts} $results={4} $label={السياسة}</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <b:include name='html-content'/>
    </b:includable>
          </b:widget>
          <b:widget id='HTML5' locked='false' title='تعليقات' type='HTML' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='content'>{getPosts} $results={3} $type={comments}</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <b:include name='html-content'/>
    </b:includable>
          </b:widget>
          <b:widget id='Label1' locked='false' title='فئات' type='Label' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
              <b:widget-setting name='display'>LIST</b:widget-setting>
              <b:widget-setting name='selectedLabelsList'/>
              <b:widget-setting name='showType'>ALL</b:widget-setting>
              <b:widget-setting name='showFreqNumbers'>true</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
            <b:includable id='cloud'>
      <ul class='cloud-style'>
        <b:loop values='data:labels' var='label'>
          <li><a class='label-name btn' expr:href='data:label.url'><data:label.name/><b:if cond='data:this.showFreqNumbers'><b:class name='has-count'/><span class='label-count count-style'>(<data:label.count/>)</span></b:if></a></li>
        </b:loop>
      </ul>
    </b:includable>
            <b:includable id='content'>
      <div class='widget-content'>
        <b:class expr:name='data:this.display + &quot;-label&quot;'/>
        <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
        <b:include cond='data:this.display == &quot;cloud&quot;' name='cloud'/>
      </div>
    </b:includable>
            <b:includable id='list'>
      <ul class='list-style'>
        <b:loop values='data:labels' var='label'>
          <li><a class='label-name' expr:href='data:label.url'><data:label.name/><b:if cond='data:this.showFreqNumbers'><b:class name='has-count'/><span class='label-count count-style'>(<data:label.count/>)</span></b:if></a></li>
        </b:loop>
      </ul>
    </b:includable>
          </b:widget>
          <b:widget id='Label2' locked='false' title='العلامات الرئيسية' type='Label' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
              <b:widget-setting name='display'>CLOUD</b:widget-setting>
              <b:widget-setting name='selectedLabelsList'/>
              <b:widget-setting name='showType'>ALL</b:widget-setting>
              <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
            <b:includable id='cloud'>
      <ul class='cloud-style'>
        <b:loop values='data:labels' var='label'>
          <li><a class='label-name btn' expr:href='data:label.url'><data:label.name/><b:if cond='data:this.showFreqNumbers'><b:class name='has-count'/><span class='label-count count-style'>(<data:label.count/>)</span></b:if></a></li>
        </b:loop>
      </ul>
    </b:includable>
            <b:includable id='content'>
      <div class='widget-content'>
        <b:class expr:name='data:this.display + &quot;-label&quot;'/>
        <b:include cond='data:this.display == &quot;list&quot;' name='list'/>
        <b:include cond='data:this.display == &quot;cloud&quot;' name='cloud'/>
      </div>
    </b:includable>
            <b:includable id='list'>
      <ul class='list-style'>
        <b:loop values='data:labels' var='label'>
          <li><a class='label-name' expr:href='data:label.url'><data:label.name/><b:if cond='data:this.showFreqNumbers'><b:class name='has-count'/><span class='label-count count-style'>(<data:label.count/>)</span></b:if></a></li>
        </b:loop>
      </ul>
    </b:includable>
          </b:widget>
          <b:widget id='Header1' locked='false' title='step news reviews (رأس الصفحة)' type='Header' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='displayUrl'/>
              <b:widget-setting name='displayHeight'>0</b:widget-setting>
              <b:widget-setting name='sectionWidth'>752</b:widget-setting>
              <b:widget-setting name='useImage'>false</b:widget-setting>
              <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
              <b:widget-setting name='imagePlacement'>BEHIND</b:widget-setting>
              <b:widget-setting name='displayWidth'>0</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include cond='data:imagePlacement in {&quot;REPLACE&quot;, &quot;BEFORE_DESCRIPTION&quot;}' name='image'/>
      <b:include cond='data:imagePlacement == &quot;BEHIND&quot;' name='title'/>
    </b:includable>
            <b:includable id='behindImageStyle'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='description'><b:comment>Replaced</b:comment></b:includable>
            <b:includable id='image'>
      <a class='logo-img' expr:href='data:blog.homepageUrl.canonical'>
        <img expr:alt='data:blog.title.escaped' expr:height='data:height' expr:src='data:image' expr:title='data:blog.title.escaped' expr:width='data:width'/>
        <b:if cond='data:view.isMultipleItems'><b:if cond='data:widget.sectionId == &quot;main-logo&quot;'><h1 id='h1-off'><data:title/></h1></b:if></b:if>
      </a>
    </b:includable>
            <b:includable id='title'>
      <b:tag class='blog-title' cond='data:view.isMultipleItems' name='h1'>
        <b:tag class='blog-title' cond='!data:view.isMultipleItems' name='span'>
          <b:tag expr:href='data:blog.homepageUrl.canonical' name='a'>
            <data:title/>
          </b:tag>
        </b:tag>
      </b:tag>
    </b:includable>
          </b:widget>
          <b:widget cond='(!data:view.isSearch AND !data:view.isArchive) AND !data:view.isPreview' id='HTML20' locked='false' title='Sticky Ads (desktop only)' type='HTML' version='2' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'/>
            </b:widget-settings>
            <b:includable id='main'>
      <b:include name='html-content'/>
    </b:includable>
            <b:includable id='widget-title'><b:comment>Don&#39;t show.</b:comment></b:includable>
          </b:widget>
          <b:widget cond='data:view.isHomepage' id='HTML21' locked='false' title='RANDOM / BY LABEL (Style 1)' type='HTML' version='2' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[label: 'random', num: 4, showComment: true, showLabel: true, showSnippet: true, showTime: true, showText: 'Show All']]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <div class='widget-content'>
        <div class='widget-title f'>
          <b:include name='widget-title'/>
          <span class='title-label tx-sm'><span class='skl-bottom two r'/></span>
        </div>
        <div class='custom-1-inner'>
          <div class='skl g'>
            <b:include name='skeleton-1'/>
            <b:include name='skeleton-1'/>
            <b:include name='skeleton-1'/>
            <b:include name='skeleton-1'/>
          </div>
        </div>
      </div>
      <script>var <data:widget.instanceId/>ar = new Array(); <data:widget.instanceId/>ar.push({<data:content/>});</script>
    </b:includable>
          </b:widget>
          <b:widget cond='data:view.isHomepage' id='HTML22' locked='false' title='RANDOM / BY LABEL (Style 1)' type='HTML' version='2' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[label: 'random', num: 4, showComment: true, showLabel: true, showSnippet: true, showTime: true, showText: 'Show All']]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <div class='widget-content'>
        <div class='widget-title f'>
          <b:include name='widget-title'/>
          <span class='title-label tx-sm'><span class='skl-bottom two r'/></span>
        </div>
        <div class='custom-1-inner'>
          <div class='skl g'>
            <b:include name='skeleton-1'/>
            <b:include name='skeleton-1'/>
            <b:include name='skeleton-1'/>
            <b:include name='skeleton-1'/>
          </div>
        </div>
      </div>
      <script>var <data:widget.instanceId/>ar = new Array(); <data:widget.instanceId/>ar.push({<data:content/>});</script>
    </b:includable>
          </b:widget>
          <b:widget id='HTML23' locked='false' title='RANDOM / BY LABEL (Style 2)' type='HTML' version='2' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[label: 'random', num: 3, showComment: false, showLabel: false, showText: 'Show All']]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <div class='widget-content'>
        <div class='widget-title f'>
          <b:include name='widget-title'/>
          <span class='title-label tx-sm'><span class='skl-bottom two r'/></span>
        </div>
        <div class='custom-2-inner g'>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
        </div>
      </div>
      <script>var <data:widget.instanceId/>ar = new Array(); <data:widget.instanceId/>ar.push({<data:content/>});</script>
    </b:includable>
          </b:widget>
          <b:widget id='HTML24' locked='false' title='RANDOM / BY LABEL (Style 2)' type='HTML' version='2' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[label: 'random', num: 3, showComment: false, showLabel: false, showText: 'Show All']]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <div class='widget-content'>
        <div class='widget-title f'>
          <b:include name='widget-title'/>
          <span class='title-label tx-sm'><span class='skl-bottom two r'/></span>
        </div>
        <div class='custom-2-inner g'>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
        </div>
      </div>
      <script>var <data:widget.instanceId/>ar = new Array(); <data:widget.instanceId/>ar.push({<data:content/>});</script>
    </b:includable>
          </b:widget>
          <b:widget id='HTML25' locked='false' title='RANDOM / BY LABEL (Style 3)' type='HTML' version='2' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[label: 'random', num: 6, showComment: true, showLabel: true, showSnippet: true, showTime: true, showText: 'Show All']]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <div class='widget-title f'>
        <b:include name='widget-title'/>
        <span class='title-label tx-sm'><span class='skl-bottom two r'/></span>
      </div>
      <div class='widget-content swipe'>
        <div class='swipe-inner f'>
          <b:include name='skeleton-1'/>
          <b:include name='skeleton-1'/>
          <b:include name='skeleton-1'/>
          <b:include name='skeleton-1'/>
          <b:include name='skeleton-1'/>
          <b:include name='skeleton-1'/>
        </div>
      </div>
      <script>var <data:widget.instanceId/>ar = new Array(); <data:widget.instanceId/>ar.push({<data:content/>});</script>
    </b:includable>
          </b:widget>
          <b:widget id='HTML26' locked='false' title='RANDOM / BY LABEL (Style 4)' type='HTML' version='2' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[label: 'random', num: 6, showLabel: true, showText: 'Show All']]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <div class='widget-title f'>
        <b:include name='widget-title'/>
        <span class='title-label tx-sm'><span class='skl-bottom two r'/></span>
      </div>
      <div class='widget-content swipe'>
        <ul class='swipe-inner f'>
          <b:include name='skeleton-6'/>
          <b:include name='skeleton-6'/>
          <b:include name='skeleton-6'/>
          <b:include name='skeleton-6'/>
          <b:include name='skeleton-6'/>
          <b:include name='skeleton-6'/>
        </ul>
      </div>
      <script>var <data:widget.instanceId/>ar = new Array(); <data:widget.instanceId/>ar.push({<data:content/>});</script>
    </b:includable>
          </b:widget>
          <b:widget id='HTML27' locked='false' title='' type='HTML' visible='false'>
            <b:includable id='main'>
      <b:include name='html-content'/>
    </b:includable>
          </b:widget>
          <b:widget id='HTML28' locked='false' title='Info' type='HTML' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[Harga: <b>Rp 230.000</b> ($23)<br/>Rilisan Terbaru: <b>v3</b><br/>Tanggal Rilis: <b>12 Februari 2023</b>]]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <b:include name='html-content'/>
    </b:includable>
          </b:widget>
          <b:widget id='HTML29' locked='false' title='Copyright' type='HTML' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[Copyright &#169; <span id='cpr'></span>]]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'><data:content/></b:includable>
            <b:includable id='widget-title'><b:comment>Don&#39;t show.</b:comment></b:includable>
          </b:widget>
          <b:widget id='Profile1' locked='false' title='About Me' type='Profile' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='showaboutme'>true</b:widget-setting>
              <b:widget-setting name='showlocation'>false</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
            <b:includable id='authorProfileImage' var='this'>
      <img class='profile-img' expr:alt='data:messages.myPhoto' expr:src='resizeImage(data:authorPhoto.image, 50, &quot;1:1&quot;)'/>
    </b:includable>
            <b:includable id='content'>
        <b:if cond='data:team'><div class='widget-content team f'><b:include name='teamProfile'/></div><b:else/><div class='widget-content individual r'><b:include name='userProfile'/></div></b:if>
      </b:includable>
            <b:includable id='defaultProfileImage' var='this'>
      <img class='profile-img' expr:alt='data:messages.myPhoto' src='https://1.bp.blogspot.com/-QN2lgvtYZco/YN3mUSryAVI/AAAAAAAAADs/KrR-etCcvUMcPl06jopTs9pzq59IAXhMQCLcBGAsYHQ/w50-h50-p-k-no-nu/avatar.jpg'/>
    </b:includable>
            <b:includable id='profileImage'>
  <b:if cond='data:authorPhoto.image'>
    <b:include name='authorProfileImage'/>
  <b:else/>
    <b:include name='defaultProfileImage'/>
  </b:if>
</b:includable>
            <b:includable id='teamProfile'>
        <ul class='f'><b:loop values='data:authors' var='author'><li class='f'><b:include data='author' name='teamProfileLink'/></li></b:loop></ul>      
      </b:includable>
            <b:includable id='teamProfileLink'>
        <b:include name='userProfileImage'/><div class='profile-about'><div class='profile-name'><data:author.display-name/></div><a class='tx-primary tx-sm' expr:href='data:userUrl' expr:title='data:author.display-name' rel='nofollow noopener' target='_blank'><data:messages.visitProfile/></a></div>
      </b:includable>
            <b:includable id='userLocation'>
        <div class='profile-location tx-75 tx-md'><svg viewBox='0 0 24 24'><path d='M14.5103 10.7105C14.5103 9.3292 13.391 8.20996 12.0097 8.20996C10.6295 8.20996 9.51025 9.3292 9.51025 10.7105C9.51025 12.0907 10.6295 13.21 12.0097 13.21C13.391 13.21 14.5103 12.0907 14.5103 10.7105Z'/><path d='M11.9995 21C9.10148 21 4.5 15.9587 4.5 10.5986C4.5 6.40246 7.8571 3 11.9995 3C16.1419 3 19.5 6.40246 19.5 10.5986C19.5 15.9587 14.8985 21 11.9995 21Z'/></svg><data:location/></div>
      </b:includable>
            <b:includable id='userProfile'>
        <b:include name='userProfileImage'/><b:include name='userProfileInfo'/>
      </b:includable>
            <b:includable id='userProfileData'>
  <dt class='profile-data'>
    <a class='profile-link g-profile' expr:href='data:userUrl' rel='author nofollow'>
      <data:displayname/>
    </a>
  </dt>
</b:includable>
            <b:includable id='userProfileImage'>
        <b:if cond='data:authorPhoto.image'><figure class='profile-avatar ignielSquircle round'><b:class cond='!data:team' name='a'/><img expr:alt='data:author.display-name' expr:data-src='data:authorPhoto.image ? resizeImage(data:authorPhoto.image, 72, &quot;1:1&quot;) : resizeImage(&quot;https://4.bp.blogspot.com/-knbdSPw80sY/W7skQMTcLYI/AAAAAAAAGiU/pKWvU6YJHuIH0Y7i0Ks0E6iFRYk65L4RACLcBGAs/s0-rw/blogger.ico&quot;, 72, &quot;1:1&quot;)' expr:title='data:author.display-name' height='72' src='data:image/png;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==' width='72'/></figure><b:else/><div class='profile-avatar ignielSquircle round noimg f'><svg viewBox='0 0 24 24'><path d='M11.8445 21.6618C8.15273 21.6618 5 21.0873 5 18.7865C5 16.4858 8.13273 14.3618 11.8445 14.3618C15.5364 14.3618 18.6891 16.4652 18.6891 18.766C18.6891 21.0658 15.5564 21.6618 11.8445 21.6618Z'/><path d='M11.8372 11.1735C14.26 11.1735 16.2236 9.2099 16.2236 6.78718C16.2236 4.36445 14.26 2.3999 11.8372 2.3999C9.41452 2.3999 7.44998 4.36445 7.44998 6.78718C7.4418 9.20172 9.3918 11.1654 11.8063 11.1735C11.8172 11.1735 11.8272 11.1735 11.8372 11.1735Z'/></svg></div></b:if>
      </b:includable>
            <b:includable id='userProfileInfo'>
        <div class='profile-inner bg-100'><div class='t'><b:if cond='data:displayname != &quot;&quot;'><data:displayname/><b:else/>User</b:if></div><b:if cond='data:aboutme != &quot;&quot; OR (data:showlocation and data:location != &quot;&quot;)'><b:include name='userProfileText'/></b:if></div>
      </b:includable>
            <b:includable id='userProfileText'>
        <b:include cond='data:showlocation and data:location != &quot;&quot;' name='userLocation'/><b:if cond='data:aboutme != &quot;&quot;'><div class='profile-text tx-75'><data:aboutme/></div><b:include name='viewProfileLink'/></b:if>
      </b:includable>
            <b:includable id='viewProfileLink'>
        <div class='profile-link tx-md'><a class='tx-primary' expr:href='data:userUrl' expr:title='data:messages.visitProfile' rel='nofollow noopener' target='_blank'><data:messages.visitProfile/></a></div>
      </b:includable>
          </b:widget>
          <b:widget id='BlogArchive1' locked='false' title='' type='BlogArchive' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='showStyle'>FLAT</b:widget-setting>
              <b:widget-setting name='yearPattern'>yyyy</b:widget-setting>
              <b:widget-setting name='showWeekEnd'>true</b:widget-setting>
              <b:widget-setting name='monthPattern'>MMMM</b:widget-setting>
              <b:widget-setting name='dayPattern'>MMM dd</b:widget-setting>
              <b:widget-setting name='weekPattern'>MM/dd</b:widget-setting>
              <b:widget-setting name='chronological'>false</b:widget-setting>
              <b:widget-setting name='showPosts'>true</b:widget-setting>
              <b:widget-setting name='frequency'>MONTHLY</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
        <b:with value='data:messages.archive' var='defaultTitle'><b:include name='super.main'/></b:with>
      </b:includable>
            <b:includable id='content'>
        <div class='widget-content'><b:include cond='data:this.style == &quot;FLAT&quot;' name='flat'/><b:include cond='data:this.style == &quot;HIERARCHY&quot;' data='data' name='interval'/><b:include cond='data:this.style == &quot;MENU&quot;' name='menu'/><b:class cond='data:this.style == &quot;FLAT&quot;' name='flat'/><b:class cond='data:this.style == &quot;HIERARCHY&quot;' name='hier'/><b:class cond='data:this.style == &quot;MENU&quot;' name='dropdown'/></div>
      </b:includable>
            <b:includable id='extendarch'>
        <b:with value='data:limit ?: 6' var='limit'><b:with expr:var='data:itemSet' value='data:items take data:limit'><b:include expr:name='data:itemsMarkup'/></b:with><b:if cond='data:items.length gt data:limit'><input class='check' expr:id='&quot;show-&quot; + data:widget.instanceId' type='checkbox'/><b:with expr:var='data:itemSet' value='data:items skip data:limit'><div class='archive-remaining h'><b:include expr:name='data:itemsMarkup'/></div><label class='show-more tx-md pointer' expr:aria-label='data:messages.archive' expr:for='&quot;show-&quot; + data:widget.instanceId'><span class='more tx-primary'><data:messages.showMore/> <b:with value='data:items skip data:limit' var='total'>+<data:total.length/></b:with></span><span class='tx-primary h'><data:messages.showLess/></span></label></b:with></b:if></b:with>
      </b:includable>
            <b:includable id='flat'>
        <b:include data='{ items: data:this.data, itemSet: &quot;data&quot;, itemsMarkup: &quot;flatcontent&quot; }' name='extendarch'/>
      </b:includable>
            <b:includable id='flatcontent'>
        <ul><b:class expr:name='data:this.style'/><b:class expr:name='data:this.style == &quot;FLAT&quot; ? &quot;g&quot; : &quot;&quot;'/><b:loop values='data:data' var='archive'><li><a expr:href='data:archive.url' expr:title='data:archive.name'><data:archive.name/></a><span class='count tx-75 tx-sm'><data:archive.post-count/></span></li></b:loop></ul>
      </b:includable>
            <b:includable id='hierarchy'>
        <b:include data='{items: data:this.data, itemSet: &quot;data&quot;, itemsMarkup: &quot;super.hierarchy&quot;}' name='extendableItems'/>
      </b:includable>
            <b:includable id='interval' var='intervals'>
        <ul><b:loop values='data:intervals' var='interval'><li><div class='hier-top f'><span><data:interval.name/></span></div><b:loop cond='data:interval.data' values='data:interval.data' var='int'><b:if cond='data:int.posts'><details><b:attr cond='data:view.url == data:int.url' name='open' value='open'/><b:class cond='data:view.url == data:int.url' name='open'/><summary class='hier-top f'><b:class cond='data:int.posts' name='pointer'/><span><data:int.name/></span></summary><b:class cond='data:int.posts' name='haspost'/><b:include cond='data:int.data' data='int.data' name='interval'/><b:include cond='data:int.posts' data='int.posts' name='posts'/></details><b:else/><a class='tx-primary' expr:href='data:int.url' expr:title='data:int.name'><data:int.name/><span class='tx-sm'>(<data:int.post-count/>)</span></a></b:if></b:loop></li></b:loop></ul>
      </b:includable>
            <b:includable id='menu' var='data'>
        <select class='tx-100' onchange='location = this.value;'><option expr:value='data:blog.homepageUrl'><data:messages.archive/></option><b:loop values='data:this.data' var='i'><option expr:value='data:i.url'><data:i.name/> (<data:i.post-count/>)</option></b:loop>
        </select>
      </b:includable>
            <b:includable id='posts' var='posts'>
        <ol class='post'><b:loop values='data:posts' var='post'><li><a class='tx-75' expr:href='data:post.url' expr:title='data:post.title'><data:post.title/></a></li></b:loop></ol>
      </b:includable>
          </b:widget>
          <b:widget id='HTML30' locked='false' title='Attribution' type='HTML' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[Theme by <a href='Link' title='Igniel' target='_blank' rel='noopener'>Igniel</a>]]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'><data:content/></b:includable>
            <b:includable id='widget-title'><b:comment>Don&#39;t show.</b:comment></b:includable>
          </b:widget>
          <b:widget id='HTML11' locked='false' title='RANDOM / BY LABEL (Style 1)' type='HTML' version='2' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[label: 'random', num: 6, showComment: true, showLabel: true, showSnippet: true, showTime: true, showText: 'Show All']]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <div class='widget-content'>
        <div class='widget-title f'>
          <b:include name='widget-title'/>
          <span class='title-label tx-sm'><span class='skl-bottom two r'/></span>
        </div>
        <div class='custom-1-inner'>
          <div class='skl g'>
            <b:include name='skeleton-1'/>
            <b:include name='skeleton-1'/>
            <b:include name='skeleton-1'/>
            <b:include name='skeleton-1'/>
          </div>
        </div>
      </div>
      <!-- <script>cus.push({<data:widget.instanceId/>: {<data:content/>}});</script> -->
      <script>var <data:widget.instanceId/>ar = new Array(); <data:widget.instanceId/>ar.push({<data:content/>});</script>
    </b:includable>
          </b:widget>
          <b:widget id='HTML13' locked='false' title='RANDOM / BY LABEL (Style 2)' type='HTML' version='2' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[label: 'random', num: 6, showComment: false, showLabel: false, showText: 'Show All']]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <div class='widget-content'>
        <div class='widget-title f'>
          <b:include name='widget-title'/>
          <span class='title-label tx-sm'><span class='skl-bottom two r'/></span>
        </div>
        <div class='custom-2-inner g'>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
        </div>
      </div>
      <script>var <data:widget.instanceId/>ar = new Array(); <data:widget.instanceId/>ar.push({<data:content/>});</script>
    </b:includable>
          </b:widget>
          <b:widget id='HTML14' locked='false' title='RANDOM / BY LABEL (Style 2)' type='HTML' version='2' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[label: 'random', num: 6, showComment: false, showLabel: false, showText: 'Show All']]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <div class='widget-content'>
        <div class='widget-title f'>
          <b:include name='widget-title'/>
          <span class='title-label tx-sm'><span class='skl-bottom two r'/></span>
        </div>
        <div class='custom-2-inner g'>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
          <b:include name='skeleton-2'/>
        </div>
      </div>
      <script>var <data:widget.instanceId/>ar = new Array(); <data:widget.instanceId/>ar.push({<data:content/>});</script>
    </b:includable>
          </b:widget>
          <b:widget id='HTML17' locked='false' title='RANDOM / BY LABEL (Style 3)' type='HTML' version='2' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[label: 'random', num: 6, showComment: true, showLabel: true, showSnippet: true, showTime: true, showText: 'Show All']]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <div class='widget-title f'>
        <b:include name='widget-title'/>
        <span class='title-label tx-sm'><span class='skl-bottom two r'/></span>
      </div>
      <div class='widget-content swipe'>
        <div class='swipe-inner f'>
          <b:include name='skeleton-1'/>
          <b:include name='skeleton-1'/>
          <b:include name='skeleton-1'/>
          <b:include name='skeleton-1'/>
        </div>
      </div>
      <script>var <data:widget.instanceId/>ar = new Array(); <data:widget.instanceId/>ar.push({<data:content/>});</script>
    </b:includable>
          </b:widget>
          <b:widget id='HTML18' locked='false' title='RANDOM / BY LABEL (Style 4)' type='HTML' version='2' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[label: 'random', num: 6, showLabel: true, showText: 'Show All']]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <div class='widget-title f'>
        <b:include name='widget-title'/>
        <span class='title-label tx-sm'><span class='skl-bottom two r'/></span>
      </div>
      <div class='widget-content swipe'>
        <ul class='swipe-inner f'>
          <b:include name='skeleton-6'/>
          <b:include name='skeleton-6'/>
          <b:include name='skeleton-6'/>
          <b:include name='skeleton-6'/>
          <b:include name='skeleton-6'/>
          <b:include name='skeleton-6'/>
        </ul>
      </div>
      <script>var <data:widget.instanceId/>ar = new Array(); <data:widget.instanceId/>ar.push({<data:content/>});</script>
    </b:includable>
          </b:widget>
          <b:widget id='HTML4' locked='false' title='Navigation' type='HTML' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='content'/>
            </b:widget-settings>
            <b:includable id='main'><b:attr name='class' value='links box-shadow a'/><div class='head f'><figure class='ava ignielSquircle'><img alt='Author' class='lazy' data-src='https://4.bp.blogspot.com/-1eSzIPykBbA/W7TEES3n5PI/AAAAAAAAGeA/NWfEPstRSFspDaGDP6_VBjxTa38mVAHlwCPcBGAYYCw/s72-rw/Lain.jpg' height='72' src='data:image/png;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==' title='Author' width='72'/></figure><div class='info f'><div class='t'>Your Name</div><div class='follow tx-md'><a class='tx-primary' expr:href='&quot;https://www.blogger.com/follow-blog.g?blogID=&quot; + data:blog.blogId' rel='nofollow noopener' target='_blank' title='Follow'>FOLLOW</a></div></div><b:include data='{class: &quot; h&quot;, num: &quot;2&quot;}' name='mode'/></div><nav aria-label='Links' class='me' itemscope='itemscope' itemtype='https://schema.org/SiteNavigationElement'><ul><data:content/></ul></nav><div class='social f'>
<a aria-label='Facebook' class='fb' href='https://www.facebook.com/#' rel='nofollow noopener' target='_blank' title='Facebook'>
  <svg class='fill' viewBox='0 0 64 64'>
    <path d='M59.5 1H4.5C2.5 1 1 2.6 1 4.5V59.5C1 61.5 2.6 63 4.5 63H34.1V38.9H26.1V29.6H34.1V22.7C34.1 14.7 38.9 10.3 46.1 10.3C48.5 10.3 50.9 10.4 53.3 10.7V19H48.5C44.7 19 43.9 20.8 43.9 23.5V29.4H53L51.7 38.8H43.7V62.6H59.5C61.5 62.6 63 61.1 63 59.1V4.5C62.9 2.5 61.3 1 59.5 1Z'/>
  </svg>
</a>
<a aria-label='Instagram' class='ig' href='https://www.instagram.com/#' rel='nofollow noopener' target='_blank' title='Instagram'>
  <svg class='fill' viewBox='0 0 64 64'>
    <path d='M62.9 19.2C62.8 16 62.2 13.7 61.5 11.6C60.8 9.5 59.7 7.8 58 6.1C56.3 4.4 54.6 3.4 52.6 2.6C50.6 1.8 48.4 1.3 45 1.2C41.5 1 40.5 1 32 1C23.5 1 22.6 1 19.2 1.1C15.8 1.2 13.7 1.8 11.6 2.5C9.5 3.2 7.8 4.4 6.1 6.1C4.4 7.8 3.3 9.5 2.6 11.6C1.8 13.6 1.3 15.8 1.2 19.2C1.1 22.6 1 23.5 1 32C1 40.5 1 41.4 1.1 44.8C1.2 48.2 1.8 50.3 2.5 52.4C3.2 54.5 4.3 56.2 6 57.9C7.7 59.6 9.5 60.7 11.5 61.4C13.5 62.1 15.7 62.7 19.1 62.8C22.5 63 23.4 63 31.9 63C40.4 63 41.3 63 44.7 62.9C48.1 62.8 50.2 62.2 52.3 61.5C54.4 60.8 56.1 59.7 57.8 58C59.5 56.3 60.6 54.5 61.3 52.5C62 50.5 62.6 48.3 62.7 44.9C62.8 41.7 62.8 40.7 62.8 32.2C62.8 23.7 63 22.6 62.9 19.2ZM57.3 44.5C57.2 47.5 56.6 49.1 56.2 50.3C55.6 51.7 54.9 52.8 53.8 53.8C52.7 54.9 51.7 55.5 50.3 56.2C49.2 56.6 47.6 57.2 44.5 57.3C41.3 57.3 40.3 57.3 32.1 57.3C23.9 57.3 22.8 57.3 19.6 57.2C16.6 57.1 15 56.5 13.8 56.1C12.4 55.5 11.3 54.8 10.3 53.7C9.2 52.6 8.6 51.6 7.9 50.2C7.5 49.1 6.9 47.5 6.8 44.4C6.8 41.3 6.8 40.3 6.8 32C6.8 23.7 6.8 22.7 6.9 19.5C7 16.5 7.6 14.9 8 13.7C8.6 12.3 9.3 11.2 10.3 10.2C11.4 9.1 12.4 8.5 13.8 7.9C14.9 7.5 16.5 6.9 19.6 6.8C22.8 6.7 23.8 6.7 32.1 6.7C40.4 6.7 41.4 6.7 44.6 6.8C47.6 6.9 49.2 7.5 50.4 7.9C51.8 8.5 52.9 9.2 53.9 10.2C55 11.3 55.6 12.3 56.3 13.7C56.7 14.8 57.3 16.4 57.4 19.5C57.5 22.7 57.5 23.7 57.5 32C57.5 40.3 57.4 41.3 57.3 44.5Z'/>
    <path d='M32.0016 16.0996C23.1016 16.0996 16.1016 23.2996 16.1016 31.9996C16.1016 40.8996 23.3016 47.8996 32.0016 47.8996C40.7016 47.8996 48.0016 40.8996 48.0016 31.9996C48.0016 23.0996 40.9016 16.0996 32.0016 16.0996ZM32.0016 42.3996C26.2016 42.3996 21.6016 37.6996 21.6016 31.9996C21.6016 26.2996 26.3016 21.5996 32.0016 21.5996C37.8016 21.5996 42.4016 26.1996 42.4016 31.9996C42.4016 37.7996 37.8016 42.3996 32.0016 42.3996Z'/>
    <path d='M48.7 19.1002C50.7435 19.1002 52.4 17.4436 52.4 15.4002C52.4 13.3567 50.7435 11.7002 48.7 11.7002C46.6565 11.7002 45 13.3567 45 15.4002C45 17.4436 46.6565 19.1002 48.7 19.1002Z'/>
  </svg>
</a>
<a aria-label='Tiktok' class='tt' href='https://www.tiktok.com/#' rel='nofollow noopener' target='_blank' title='Tiktok'>
  <svg class='fill' viewBox='0 0 64 64'>
    <path d='M55.619 1H8.38095C4.3111 1 1 4.3111 1 8.38095V55.619C1 59.6889 4.3111 63 8.38095 63H55.619C59.6889 63 63 59.6889 63 55.619V8.38095C63 4.3111 59.6889 1 55.619 1ZM49.7231 28.0482C49.3846 28.0811 49.0447 28.0984 48.7046 28.0999C46.8681 28.1002 45.0604 27.6431 43.4448 26.7699C41.8291 25.8968 40.4563 24.635 39.4503 23.0986V40.1294C39.4503 42.6189 38.7121 45.0526 37.329 47.1226C35.9458 49.1926 33.9799 50.806 31.6799 51.7587C29.3798 52.7114 26.8489 52.9607 24.4072 52.475C21.9654 51.9893 19.7226 50.7905 17.9622 49.0301C16.2018 47.2697 15.0029 45.0268 14.5172 42.5851C14.0316 40.1433 14.2808 37.6124 15.2335 35.3124C16.1863 33.0123 17.7996 31.0464 19.8696 29.6633C21.9396 28.2801 24.3733 27.5419 26.8629 27.5419C27.1256 27.5419 27.3825 27.5655 27.6408 27.5818V33.7847C27.3825 33.7537 27.1286 33.7065 26.8629 33.7065C25.159 33.7065 23.5249 34.3833 22.3201 35.5881C21.1153 36.7929 20.4385 38.427 20.4385 40.1309C20.4385 41.8347 21.1153 43.4688 22.3201 44.6736C23.5249 45.8784 25.159 46.5552 26.8629 46.5552C30.4116 46.5552 33.5456 43.7593 33.5456 40.2106L33.6076 11.2861H39.5419C39.813 13.8645 40.9818 16.2656 42.844 18.0696C44.7062 19.8735 47.1433 20.9654 49.729 21.1544V28.0482'/>
  </svg>
</a>
<a aria-label='Twitter' class='twt' href='https://twitter.com/#' rel='nofollow noopener' target='_blank' title='Twitter'>
  <svg class='fill' viewBox='0 0 64 64'>
    <path d='M20.3 57.3996C43.9 57.3996 56.7 37.8996 56.7 20.9996C56.7 20.5996 56.7 19.8996 56.6 19.2996C59.1 17.4996 61.3 15.1996 63 12.6996C60.6 13.7996 58.2 14.3996 55.7 14.6996C58.4 13.0996 60.4 10.5996 61.3 7.59961C58.8 8.99961 56.2 10.0996 53.1 10.6996C50.7 8.19961 47.5 6.59961 43.8 6.59961C36.7 6.59961 30.9 12.3996 30.9 19.4996C30.9 20.4996 31 21.4996 31.2 22.4996C20.9 21.7996 11.5 16.6996 5.1 8.99961C4 10.9996 3.4 13.0996 3.4 15.3996C3.4 19.8996 5.7 23.6996 9.2 25.9996C7.1 25.8996 5.1 25.2996 3.4 24.3996C3.4 24.4996 3.4 24.4996 3.4 24.4996C3.4 30.5996 7.8 35.8996 13.6 37.0996C12.5 37.3996 11.3 37.4996 10.4 37.4996C9.6 37.4996 8.7 37.3996 8 37.1996C9.7 42.2996 14.4 45.9996 20 46.0996C15.6 49.4996 10.1 51.5996 4.2 51.5996C3 51.7996 2 51.5996 1 51.4996C6.4 55.2996 13.1 57.3996 20.3 57.3996Z'/>
  </svg>
</a>
<a aria-label='YouTube' class='yt' href='https://www.youtube.com/#' rel='nofollow noopener' target='_blank' title='YouTube'>
  <svg class='fill' viewBox='0 0 64 64'>
    <path d='M61.7 17.0998C61 14.3998 58.9 12.2998 56.2 11.5998C51.4 10.2998 32 10.2998 32 10.2998C32 10.2998 12.6 10.2998 7.8 11.5998C5.1 12.2998 3 14.3998 2.3 17.0998C1 21.9998 1 31.9998 1 31.9998C1 31.9998 1 42.0998 2.3 46.8998C3 49.5998 5.1 51.6998 7.8 52.3998C12.6 53.6998 32 53.6998 32 53.6998C32 53.6998 51.4 53.6998 56.2 52.3998C58.9 51.6998 61 49.5998 61.7 46.8998C63 42.0998 63 31.9998 63 31.9998C63 31.9998 63 21.9998 61.7 17.0998ZM25.8 41.2998V22.6998L41.9 31.9998L25.8 41.2998Z'/>
  </svg>
</a>
</div></b:includable>
            <b:includable id='widget-title'><b:comment>Don&#39;t show.</b:comment></b:includable>
          </b:widget>
          <b:widget id='HTML3' locked='false' title='Menu' type='HTML' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='content'/>
            </b:widget-settings>
            <b:includable id='main'><b:attr name='class' value=''/><nav aria-label='Menu' class='nav'><ul><data:content/></ul></nav></b:includable>
            <b:includable id='widget-title'><b:comment>Don&#39;t show.</b:comment></b:includable>
          </b:widget>
          <b:widget id='HTML6' locked='false' title='Billboard Ads (Iklan Besar)' type='HTML' version='2' visible='false'>
            <b:widget-settings>
              <b:widget-setting name='content'/>
            </b:widget-settings>
            <b:includable id='main'><b:attr name='class' value='billboard'/><data:content/></b:includable>
            <b:includable id='widget-title'><b:comment>Don&#39;t show.</b:comment></b:includable>
          </b:widget>
          <b:widget id='HTML2' locked='false' title='CONFIGURATION' type='HTML' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='content'>const igniplex = {
  ads: {
    url: &#39;&#39;,
    lazyAds: true,
    adblock: false,
    adblockTitle: &#39;Matikan AdBlock&#39;,
    adblockText: &#39;Agar blog ini tetap berjalan, matikan AdBlock atau masukkan blog ini ke dalam whitelist. Terima kasih.&#39;,
    adblockClose: &#39;Tutup&#39;
  },
  noimage: &#39;https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhYsIrfaJQ2BytaxI1q1G7q2EUA3g5TlaVeDxmihX66oHzidd9bewbuP7_cQJXgRuDF0dps3MCJcQPHEQ1SPTE8nd-Hj4uXLq5I9pK88gD6n6Z5WmUz5v7bq2g0rxn5dRg7WmNB51iNxqaGjeE2vh6jl4KzeGlb3eKBUE5J1Lh4Dw3wfrjTuQ5AKahQRQ/s0/igniplex-noimage.png&#39;,
  syntax: &#39;Kode berhasil disalin&#39;,
  youtube: &#39;sddefault&#39;,
  infiniteScroll: {
    load: &#39;Muat artikel&#39;,
    loading: &#39;Memuat...&#39;,
    loaded: &#39;Selesai&#39;,
    error: &#39;Error&#39;,
  },
  pagination: {
    titleText: &#39;Halaman:&#39;,
    allText: &#39;Lihat Semua&#39;,
  },
  postEmpty: {
    label: &#39;random&#39;,
    num: 4,
    showImage: true,
    showComment: true,
    showLabel: true,
  },
  relatedBottom: {
    num: 6,
    showImage: true,
    showSnippet: true,
    showTime: true,
  },
  relatedMiddle: {
    num: 4,
    showImage: true,
  },
  toc: {
    type: 1,
    title: &#39;Daftar Isi&#39;,
    selector: &#39;h2, h3, h4&#39;,
    overlay: true,
  },
  speech: {
    lang: &#39;id-ID&#39;,
    speed: 1,
    playText: &#39;Memutar...&#39;,
    pauseText: &#39;Jeda&#39;,
    finishText: &#39;Selesai&#39;,
    exception: [&#39;.toc&#39;, &#39;.igniplexTengah&#39;, &#39;.post-body pre&#39;, &#39;.tabs.syntax&#39;],
  },
  bookmark: {
    maxWidget: 5,
    maxAll: 100,
    emptyText: &#39;Tidak ada bookmark&#39;,
    moreText: &#39;Lihat selengkapnya&#39;,
    currentText: &#39;Sedang melihat halaman bookmark&#39;,
    morePage: &#39;/p/bookmark.html&#39;,
  }
};</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'><b:attr name='class' value=''/>&lt;script&gt;//&lt;![CDATA[
<data:content/>
//]]&gt;&lt;/script&gt;</b:includable>
            <b:includable id='widget-title'><b:comment>Don&#39;t show.</b:comment></b:includable>
          </b:widget>
        </b:section>
      </aside>
    </div>
  </div>
  <b:if cond='data:view.isLayoutMode or (data:view.isHomepage or (data:view.isPost and (data:skin.vars.footerad_onpost == &quot;1px&quot;))) and (data:widgets any w =&gt; w.sectionId == &quot;footer-ads&quot;)'>
    <div class='flex-c' id='footer-ads-wrap'>
      <b:class cond='data:skin.vars.footerad_border == &quot;1px&quot;' name='has-border'/>
      <b:section class='footer-ads container row-x1' id='footer-ads' maxwidgets='1' name='Footer ADS' showaddelement='yes'/>
    </div>
  </b:if>
  <footer class='flex-col' id='footer-wrapper'>
    <b:if cond='data:view.isLayoutMode or (data:widgets.Image any w =&gt; w.sectionId == &quot;buzzspot-pro-about-section&quot;)'>
      <div class='primary-footer flex-c'>
        <div class='container row-x1'>
          <b:section class='about-section flex-sb' id='buzzspot-pro-about-section' maxwidgets='2' name='About Section' showaddelement='yes'>
            <b:widget id='Image51' locked='true' title='معلومات عنا' type='Image' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='displayUrl'>https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEj3x0k1nEamHqcggzCkFqE6CtmLkCZ-qD6x8xu9zt4KB0nlRO0M5Ec6aAoAVXFz7ex8z46L9g669iTxaWjkHKd8JnLF6bBcMDA8kFv1nLI5BY-IKpSLkdwcBZiUXE4lThybI_j3lDsLIrKD1kfvC-vlKbNOgB0GTVigLr_8geqnFyNRbNVimty5BxosqGX_/s150/Picsart_23-08-15_14-04-25-406.png</b:widget-setting>
                <b:widget-setting name='displayHeight'>38</b:widget-setting>
                <b:widget-setting name='sectionWidth'>150</b:widget-setting>
                <b:widget-setting name='shrinkToFit'>true</b:widget-setting>
                <b:widget-setting name='displayWidth'>150</b:widget-setting>
                <b:widget-setting name='link'/>
                <b:widget-setting name='caption'>موقع إخباري شامل تتابعون فيه مستجدات الأحداث العربية والعالمية على مدار الساعة&#1548; وتغطية مستمرة لأخبار السياسة والرياضة والاقتصاد والعلوم والفن والتكنولوجيا.</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
              <b:includable id='content'>
      <b:include name='image-content'/>
    </b:includable>
            </b:widget>
            <b:widget id='LinkList203' locked='true' title='تابعنا' type='LinkList' visible='true'>
              <b:widget-settings>
                <b:widget-setting name='link-5'>https://www.pinterest.com</b:widget-setting>
                <b:widget-setting name='link-6'>https://www.tiktok.com/tiktok.com/@stepnewsreviews</b:widget-setting>
                <b:widget-setting name='link-3'>https://www.youtube.com</b:widget-setting>
                <b:widget-setting name='link-4'><![CDATA[https://instagram.com/stepnewsreviews?utm_source=qr&igshid=ZDc4ODBmNjlmNQ%3D%3D]]></b:widget-setting>
                <b:widget-setting name='text-1'>facebook</b:widget-setting>
                <b:widget-setting name='text-0'>{getSocial}</b:widget-setting>
                <b:widget-setting name='text-3'>youtube</b:widget-setting>
                <b:widget-setting name='text-2'>twitter</b:widget-setting>
                <b:widget-setting name='text-5'>pinterest</b:widget-setting>
                <b:widget-setting name='text-4'>instagram</b:widget-setting>
                <b:widget-setting name='text-6'>tiktok </b:widget-setting>
                <b:widget-setting name='sorting'>NONE</b:widget-setting>
                <b:widget-setting name='link-1'>https://www.facebook.com/jolin.tsai.3910?mibextid=ZbWKwL</b:widget-setting>
                <b:widget-setting name='link-2'>https://twitter.com</b:widget-setting>
                <b:widget-setting name='link-0'>#</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
              <b:includable id='content'>
      <b:include name='linklist-content'/>
    </b:includable>
            </b:widget>
          </b:section>
        </div>
      </div>
    </b:if>
    <div class='footer-bar flex-c'>
      <b:class cond='data:skin.vars.footerbar_border == &quot;1px&quot;' name='has-border'/>
      <div class='container row-x1 flex-sb'>
        <b:section class='footer-copyright' id='footer-copyright' maxwidgets='1' name='Footer Copyright' showaddelement='yes'>
          <b:widget id='Text50' locked='true' title='' type='Text' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[التصميم - <a href="https://stepnewsreviews.blogspot.com/" title="step News Rivewes">step News Rivewes</a>]]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
      <b:include name='text-content'/>
    </b:includable>
          </b:widget>
        </b:section>
        <b:section class='footer-menu' id='footer-menu' maxwidgets='1' name='Footer Menu' showaddelement='yes'>
          <b:widget id='LinkList204' locked='true' title='' type='LinkList' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='link-3'>https://stepnewsreviews.blogspot.com/p/blog-page.html</b:widget-setting>
              <b:widget-setting name='sorting'>NONE</b:widget-setting>
              <b:widget-setting name='text-1'>من نحن </b:widget-setting>
              <b:widget-setting name='link-1'>https://stepnewsreviews.blogspot.com/p/blog-page_46.html</b:widget-setting>
              <b:widget-setting name='text-0'>اتصل بنا </b:widget-setting>
              <b:widget-setting name='link-2'>https://stepnewsreviews.blogspot.com/p/blog-page_4.html</b:widget-setting>
              <b:widget-setting name='text-3'>إتفاقية الاستخدام </b:widget-setting>
              <b:widget-setting name='link-0'>/</b:widget-setting>
              <b:widget-setting name='text-2'>سياسة الخصوصية</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
            <b:includable id='content'>
      <b:include name='linklist-content'/>
    </b:includable>
          </b:widget>
        </b:section>
      </div>
    </div>
  </footer>
  <b:if cond='data:view.isLayoutMode or (data:widgets.Text any w =&gt; w.sectionId == &quot;cookie-consent-section&quot;)'>
    <div class='cookie-consent' id='buzzspot-pro-cookie-consent'>
      <b:section id='cookie-consent-section' maxwidgets='1' name='Cookie Consent' showaddelement='no'>
        <b:widget id='Text51' locked='true' title='$ok={OK, Go it!} $days={7}' type='Text' visible='true'>
          <b:widget-settings>
            <b:widget-setting name='content'><![CDATA[يستخدم موقعنا ملفات تعريف الارتباط لتحسين تجربتك. <a href="https://stepnewsreviews.blogspot.com/"a>أقرأ المزيد</a>]]></b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>
      <b:include name='text-content'/>
    </b:includable>
        </b:widget>
      </b:section>
    </div>
  </b:if>
</div>
<!-- Fixed Elements -->
<div id='fixed-elements'>
    <div id='slide-menu'>
      <div class='slide-menu-header'>
        <div class='mobile-logo'/>
        <button aria-label='Hide Menu' class='hide-mobile-menu'/>
      </div>
      <div class='slide-menu-flex'>
        <div class='mobile-menu' id='mobile-menu'/>
        <div class='mm-footer'/>
      </div>
    </div>
    <div class='overlay' id='overlay'/>
    <button aria-label='Back To Top' class='btn' id='back-top'/>
</div>
<b:if cond='data:view.isSingleItem'>
  <b:section class='hidden-widgets' deleted='true' id='hidden-widgets' maxwidgets='1' showaddelement='no'>
    <b:widget id='ContactForm1' locked='true' title='نموذج الاتصال' type='ContactForm' visible='true'>
      <b:includable id='main' var='this'>
      <b:include name='widget-title'/>
      <b:include name='content'/>
    </b:includable>
      <b:includable id='content'>
      <b:include name='contact-form-content'/>
    </b:includable>
    </b:widget>
  </b:section>
</b:if>

<!-- Main Scripts -->
<script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js' type='text/javascript'/>
<b:include name='theme-variables'/>
<script type='text/javascript'>
//<![CDATA[
/*! Theia Sticky Sidebar | v1.5.0 - https://github.com/WeCodePixels/theia-sticky-sidebar */
!function(i){i.fn.theiaStickySidebar=function(t){var e,o,a,s,n;function d(t,e){return!0===t.initialized||!(i("body").width()<t.minWidth)&&(function(t,e){t.initialized=!0,0===i("#theia-sticky-sidebar-stylesheet-"+t.namespace).length&&i("head").append(i('<style id="theia-sticky-sidebar-stylesheet-'+t.namespace+'">.theiaStickySidebar:after {content: ""; display: table; clear: both;}</style>')),e.each(function(){var e={};if(e.sidebar=i(this),e.options=t||{},e.container=i(e.options.containerSelector),0==e.container.length&&(e.container=e.sidebar.parent()),e.sidebar.parent().css("-webkit-transform","none"),e.sidebar.css({position:e.options.defaultPosition,overflow:"visible","-webkit-box-sizing":"border-box","-moz-box-sizing":"border-box","box-sizing":"border-box"}),e.stickySidebar=e.sidebar.find(".theiaStickySidebar"),0==e.stickySidebar.length){var o=/(?:text|application)\/(?:x-)?(?:javascript|ecmascript)/i;e.sidebar.find("script").filter(function(i,t){return 0===t.type.length||t.type.match(o)}).remove(),e.stickySidebar=i("<div>").addClass("theiaStickySidebar").append(e.sidebar.children()),e.sidebar.append(e.stickySidebar)}e.marginBottom=parseInt(e.sidebar.css("margin-bottom")),e.paddingTop=parseInt(e.sidebar.css("padding-top")),e.paddingBottom=parseInt(e.sidebar.css("padding-bottom"));var a,s,n,d=e.stickySidebar.offset().top,c=e.stickySidebar.outerHeight();function p(){e.fixedScrollTop=0,e.sidebar.css({"min-height":"1px"}),e.stickySidebar.css({position:"static",width:"",transform:"none"})}e.stickySidebar.css("padding-top",1),e.stickySidebar.css("padding-bottom",1),d-=e.stickySidebar.offset().top,c=e.stickySidebar.outerHeight()-c-d,0==d?(e.stickySidebar.css("padding-top",0),e.stickySidebarPaddingTop=0):e.stickySidebarPaddingTop=1,0==c?(e.stickySidebar.css("padding-bottom",0),e.stickySidebarPaddingBottom=0):e.stickySidebarPaddingBottom=1,e.previousScrollTop=null,e.fixedScrollTop=0,p(),e.onScroll=function(e){if(e.stickySidebar.is(":visible"))if(i("body").width()<e.options.minWidth)p();else{if(e.options.disableOnResponsiveLayouts)if(e.sidebar.outerWidth("none"==e.sidebar.css("float"))+50>e.container.width())return void p();var o,a,s=i(document).scrollTop(),n="static";if(s>=e.sidebar.offset().top+(e.paddingTop-e.options.additionalMarginTop)){var d,c=e.paddingTop+t.additionalMarginTop,b=e.paddingBottom+e.marginBottom+t.additionalMarginBottom,l=e.sidebar.offset().top,h=e.sidebar.offset().top+(o=e.container,a=o.height(),o.children().each(function(){a=Math.max(a,i(this).height())}),a),f=0+t.additionalMarginTop;d=e.stickySidebar.outerHeight()+c+b<i(window).height()?f+e.stickySidebar.outerHeight():i(window).height()-e.marginBottom-e.paddingBottom-t.additionalMarginBottom;var g=l-s+e.paddingTop,S=h-s-e.paddingBottom-e.marginBottom,m=e.stickySidebar.offset().top-s,y=e.previousScrollTop-s;"fixed"==e.stickySidebar.css("position")&&"modern"==e.options.sidebarBehavior&&(m+=y),"stick-to-top"==e.options.sidebarBehavior&&(m=t.additionalMarginTop),"stick-to-bottom"==e.options.sidebarBehavior&&(m=d-e.stickySidebar.outerHeight()),m=0<y?Math.min(m,f):Math.max(m,d-e.stickySidebar.outerHeight()),m=Math.max(m,g),m=Math.min(m,S-e.stickySidebar.outerHeight());var u=e.container.height()==e.stickySidebar.outerHeight();n=!u&&m==f||!u&&m==d-e.stickySidebar.outerHeight()?"fixed":s+m-e.sidebar.offset().top-e.paddingTop<=t.additionalMarginTop?"static":"absolute"}if("fixed"==n){var k=i(document).scrollLeft();e.stickySidebar.css({position:"fixed",width:r(e.stickySidebar)+"px",transform:"translateY("+m+"px)",left:e.sidebar.offset().left+parseInt(e.sidebar.css("padding-left"))-k+"px",top:"0px"})}else if("absolute"==n){var v={};"absolute"!=e.stickySidebar.css("position")&&(v.position="absolute",v.transform="translateY("+(s+m-e.sidebar.offset().top-e.stickySidebarPaddingTop-e.stickySidebarPaddingBottom)+"px)",v.top="0px"),v.width=r(e.stickySidebar)+"px",v.left="",e.stickySidebar.css(v)}else"static"==n&&p();"static"!=n&&1==e.options.updateSidebarHeight&&e.sidebar.css({"min-height":e.stickySidebar.outerHeight()+e.stickySidebar.offset().top-e.sidebar.offset().top+e.paddingBottom}),e.previousScrollTop=s}},e.onScroll(e),i(document).on("scroll."+e.options.namespace,(a=e,function(){a.onScroll(a)})),i(window).on("resize."+e.options.namespace,(s=e,function(){s.stickySidebar.css({position:"static"}),s.onScroll(s)})),"undefined"!=typeof ResizeSensor&&new ResizeSensor(e.stickySidebar[0],(n=e,function(){n.onScroll(n)}))})}(t,e),!0)}function r(i){var t;try{t=i[0].getBoundingClientRect().width}catch(i){}return void 0===t&&(t=i.width()),t}return(t=i.extend({containerSelector:"",additionalMarginTop:0,additionalMarginBottom:0,updateSidebarHeight:!0,minWidth:0,disableOnResponsiveLayouts:!0,sidebarBehavior:"modern",defaultPosition:"relative",namespace:"TSS"},t)).additionalMarginTop=parseInt(t.additionalMarginTop)||0,t.additionalMarginBottom=parseInt(t.additionalMarginBottom)||0,d(e=t,this)||(console.log("TSS: Body width smaller than options.minWidth. Init is delayed."),i(document).on("scroll."+e.namespace,(s=e,n=this,function(t){d(s,n)&&i(this).unbind(t)})),i(window).on("resize."+e.namespace,(o=e,a=this,function(t){d(o,a)&&i(this).unbind(t)}))),this}}(jQuery);

/*! pbtMenu by Pro Blogger Templates | v1.1.0 - https://probloggertemplates.com */
!function(a){a.fn.pbtMenu=function(){return this.each(function(){var $t=a(this),b=$t.find('.LinkList ul > li').children('a'),c=b.length;for(var i=0;i<c;i++){var d=b.eq(i),h=d.text();if(h.charAt(0)!=='_'){var e=b.eq(i+1),j=e.text();if(j.charAt(0)==='_'){var m=d.parent();m.append('<ul class="sub-menu sm-1"/>');}}if(h.charAt(0)==='_'){d.text(h.replace('_',''));d.parent().appendTo(m.children('.sub-menu'));}}for(var i=0;i<c;i++){var f=b.eq(i),k=f.text();if(k.charAt(0)!=='_'){var g=b.eq(i+1),l=g.text();if(l.charAt(0)==='_'){var n=f.parent();n.append('<ul class="sub-menu sm-2"/>');}}if(k.charAt(0)==='_'){f.text(k.replace('_',''));f.parent().appendTo(n.children('.sm-2'));}}$t.find('.LinkList ul li ul').parent('li').addClass('has-sub');});}}(jQuery);

/*! pbtLazy by Pro Blogger Templates | v1.3.0 - https://probloggertemplates.com */
!function(o){o.fn.pbtLazy=function(n){return n=o.extend({onScroll:!0},n),this.each(function(t,c,e){var r=o(this),l=o(window),a=r.data("src"),h="w"+Math.round(r.width()+r.width()/10)+"-h"+Math.round(r.height()+r.height()/10)+"-p-k-no-nu";function s(){var o=new Image;o.onload=function(){r.attr("style","background-image:url("+this.src+")").addClass("pbt-lazy")},o.src=t}a.match("resources.blogblog.com")&&(a="undefined"!=typeof noThumbnail?noThumbnail:"//1.bp.blogspot.com/-rI4UCIrwEI4/YN3nGkf0nCI/AAAAAAAAAD0/DQ6fW7eCps8NL7S0oh374KFg1MsWUf2GQCLcBGAsYHQ/s72-c/ptb-nth.png"),a.match("blogger.googleusercontent.com")&&a.match("=")&&(e=a.split("="),a=e[1]&&""!=e[1].trim()?e[0]+"=w72-h72-p-k-no-nu":a),a.match("blogger.googleusercontent.com")&&!a.match("=")&&(a+="=w72-h72-p-k-no-nu"),t=a.match("/s72-c")?a.replace("/s72-c","/"+h):a.match("/w72-h")?a.replace("/w72-h72-p-k-no-nu","/"+h):a.match("=w72-h")?a.replace("=w72-h72-p-k-no-nu","="+h):a,1==n.onScroll?l.on("load resize scroll",function o(){l.scrollTop()+l.height()>=r.offset().top&&(l.off("load resize scroll",o),s())}).trigger("scroll"):l.on("load",function o(){l.off("load",o),s()}).trigger("load")})}}(jQuery);

/*! pbtTicker by Pro Blogger Templates | v1.0.0 - https://probloggertemplates.com */
!function(t){t.fn.pbtTicker=function(){return this.each(function(){new class{constructor(t){this.ticker=t,this.active=0,this.tickerInit()}tickerActive(t){this.active=t,this.items.each(function(){this.classList.remove("active")}),this.items[t].classList.add("active"),this.tickerAuto()}tickerArrows(){this.ticker.append('<div class="ticker-nav"><button class="tn-prev btn" aria-label="Previous"/><button class="tn-next btn" aria-label="Next"/></div>')}prev(){this.active>0?this.tickerActive(this.active-1):this.tickerActive(this.items.length-1)}next(){this.active<this.items.length-1?this.tickerActive(this.active+1):this.tickerActive(0)}tickerNavigation(){const t=this.ticker.find(".tn-prev");this.ticker.find(".tn-next").on("click",this.next),t.on("click",this.prev)}tickerAuto(){clearTimeout(this.timeout),this.timeout=setTimeout(this.next,5e3)}tickerInit(){this.next=this.next.bind(this),this.prev=this.prev.bind(this),this.items=this.ticker.find(".pbt-ticker > *");const t=this.items.length;t&&(this.tickerActive(0),t>=2&&(this.tickerArrows(),this.tickerNavigation()))}}(t(this))})}}(jQuery);

/*! Table of Contents | v0.4.1 - https://github.com/ndabas/toc */
!function(t){"use strict";var n=function(n){return this.each(function(){var e,i,a=t(this),o=a.data(),c=[a],r=this.tagName,d=0;e=t.extend({content:"body",headings:"h1,h2,h3"},{content:o.toc||void 0,headings:o.tocHeadings||void 0},n),i=e.headings.split(","),t(e.content).find(e.headings).attr("id",function(n,e){return e||function(t){0===t.length&&(t="?");for(var n=t.replace(/[^a-zA-Z ]/g, "").replace(/\s+/g,"_"),e="",i=1;null!==document.getElementById(n+e);)e="_"+i++;return n+e}(t(this).text())}).each(function(){var n=t(this),e=t.map(i,function(t,e){return n.is(t)?e:void 0})[0];if(e>d){var a=c[0].children("li:last")[0];a&&c.unshift(t("<"+r+"/>").appendTo(a))}else c.splice(0,Math.min(d-e,Math.max(c.length-1,0)));t("<li/>").appendTo(c[0]).append(t("<a/>").text(n.text()).attr("href","#"+n.attr("id"))),d=e})})},e=t.fn.toc;t.fn.toc=n,t.fn.toc.noConflict=function(){return t.fn.toc=e,this},t(function(){n.call(t("[data-toc]"))})}(window.jQuery);

/*! jQuery replaceText | v1.1.0 - https://benalman.com/projects/jquery-replacetext-plugin */
!function(e){e.fn.replaceText=function(n,t,i){return this.each(function(){var o,r,l=this.firstChild,u=[];if(l)do{3===l.nodeType&&(r=(o=l.nodeValue).replace(n,t))!==o&&(!i&&/</.test(r)?(e(l).before(r),u.push(l)):l.nodeValue=r)}while(l=l.nextSibling);u.length&&e(u).remove()})}}(jQuery);

/*! Javascript Cookie | v1.5.1 - https://github.com/js-cookie/js-cookie */
!function(e){var n;if("function"==typeof define&&define.amd)define(["jquery"],e);else if("object"==typeof exports){try{n=require("jquery")}catch(e){}module.exports=e(n)}else{var o=window.Cookies,r=window.Cookies=e(window.jQuery);r.noConflict=function(){return window.Cookies=o,r}}}(function(e){var n=/\+/g;function o(e){return u.raw?e:encodeURIComponent(e)}function r(e){return o(u.json?JSON.stringify(e):String(e))}function t(e,o){var r=u.raw?e:function(e){0===e.indexOf('"')&&(e=e.slice(1,-1).replace(/\\"/g,'"').replace(/\\\\/g,"\\"));try{return e=decodeURIComponent(e.replace(n," ")),u.json?JSON.parse(e):e}catch(e){}}(e);return c(o)?o(r):r}function i(){for(var e,n,o=0,r={};o<arguments.length;o++)for(e in n=arguments[o])r[e]=n[e];return r}function c(e){return"[object Function]"===Object.prototype.toString.call(e)}var u=function(e,n,f){if(arguments.length>1&&!c(n)){if("number"==typeof(f=i(u.defaults,f)).expires){var s=f.expires,a=f.expires=new Date;a.setMilliseconds(a.getMilliseconds()+864e5*s)}return document.cookie=[o(e),"=",r(n),f.expires?"; expires="+f.expires.toUTCString():"",f.path?"; path="+f.path:"",f.domain?"; domain="+f.domain:"",f.secure?"; secure":""].join("")}for(var d,p=e?void 0:{},l=document.cookie?document.cookie.split("; "):[],m=0,v=l.length;m<v;m++){var g=l[m].split("="),w=(d=g.shift(),u.raw?d:decodeURIComponent(d)),j=g.join("=");if(e===w){p=t(j,n);break}e||void 0===(j=t(j))||(p[w]=j)}return p};return u.get=u.set=u,u.defaults={},u.remove=function(e,n){return u(e,"",i(n,{expires:-1})),!u(e)},e&&(e.cookie=u,e.removeCookie=u.remove),u});
//]]>
</script>
<script type='text/javascript'>
//<![CDATA[
function getAttr(t,e,a){var s=t.split("$"),o=/([^{\}]+(?=}))/g;for(let t=0;t<s.length;t++){var r=s[t].split("=");if(r[0].trim()==e)return null!=(a=r[1]).match(o)&&String(a.match(o)).trim()}return!1}function darkModeLogo(t){$("[data-dark-src]").each(function(){var e=$(this),a=e.data("dark-src"),s=e.data("src");"true"==t?e.attr("src",a):e.attr("src",s)})}function caEmpty(){var t=$("#custom-ads");!t.find(".widget").length&&t.remove()}function msgError(){return'<span class="error-msg"><b>Error:</b>&nbsp;'+pbt.noResults+"</span>"}function beforeLoader(){return'<div class="loader"></div>'}function getFeedUrl(t,e,a,s){switch(a){case"recent":s="/feeds/posts/default?alt=json&max-results="+e;break;default:s="comments"!=t?"/feeds/posts/default/-/"+a+"?alt=json&max-results="+e:"/feeds/comments/default?alt=json&max-results="+e}return s}function getPostID(t,e,a){return a=(a=t[e].id.$t)?a.split("-").pop():""}function getPostLink(t,e){for(var a=0;a<t[e].link.length;a++)if("alternate"==t[e].link[a].rel){var s=t[e].link[a].href;break}return s}function getPostTitle(t,e,a){return t[e].title.$t?t[e].title.$t:pbt.noTitle}function getPostAuthor(t,e,a,s){return s=""!=pbt.postAuthorLabel?'<span class="sp">'+pbt.postAuthorLabel+"</span>":"",pbt.postAuthor?'<span class="entry-author mi">'+s+'<span class="author-name">'+t[e].author[0].name.$t+"</span></span>":""}function getPostDate(t,e,a,s,o,r){monthNames="undefined"!=typeof monthNames?monthNames:["جانفي ","فيفري","مارس","أفريل ","ماي","جوان ","جويلية ","أوت ","سبتمبر ","أكتوبر ","نوفمبر ","ديسمبر "],dateFormat="undefined"!=typeof dateFormat?dateFormat:"{m} {d}, {y}";var n=t[e].published.$t,i=n.substring(0,4),c=n.substring(5,7),l=n.substring(8,10),d=dateFormat.replace("{m}",monthNames[parseInt(c,10)-1]).replace("{d}",l).replace("{y}",i);return r=pbt.postAuthor&&""!=pbt.postDateLabel?'<span class="sp">'+pbt.postDateLabel+"</span>":"",[1==pbt.postDate?'<span class="entry-time mi">'+r+'<time class="published" datetime="'+n+'">'+d+"</time></span>":"",1==pbt.postDate?'<span class="entry-time"><time class="published" datetime="'+n+'">'+d+"</time></span>":""]}function getPostMeta(t,e,a,s,o){return[1==pbt.postAuthor||1==pbt.postDate?'<div class="entry-meta">'+t+e[0]+"</div>":"",1==pbt.postDate?'<div class="entry-meta">'+e[1]+"</div>":""]}function getFirstImage(t){var e=(t=$("<div>").html(t)).find("img").first().attr("src"),a=e.split("/"),s="/"+a.slice(-2)[0];return 9==a.length&&(s.match(/\/s[0-9]+/g)||s.match(/\/w[0-9]+/g)||"/d"==s)&&(e=e.replace(s,"/w72-h72-p-k-no-nu")),e}function getPostImage(t,e,a,s){var o=t[e].content?t[e].content.$t:"";return a=t[e].media$thumbnail?t[e].media$thumbnail.url:"https://resources.blogblog.com/img/blank.gif",o.indexOf(o.match(/<iframe(?:.+)?src=(?:.+)?(?:www.youtube.com)/g))>-1?o.indexOf("<img")>-1?o.indexOf(o.match(/<iframe(?:.+)?src=(?:.+)?(?:www.youtube.com)/g))<o.indexOf("<img")?a.replace("img.youtube.com","i.ytimg.com").replace("/default.","/maxresdefault."):getFirstImage(o):a.replace("img.youtube.com","i.ytimg.com").replace("/default.","/maxresdefault."):o.indexOf("<img")>-1?getFirstImage(o):"https://resources.blogblog.com/img/blank.gif"}function getPostImageType(t,e){return t.match("i.ytimg.com")?" is-ytimg":""}function getPostTag(t,e,a,s,o,r){return a=t[e].category?'<span class="entry-category">'+t[e].category[0].term+"</span>":"",[1==pbt.entryTag?a:"",1==pbt.thumbTag?a:""]}function getPostSummary(t,e,a,s,o,r){return t[e].content?((r=$(t[e].content.$t)).find("td.tr-caption").text(""),o=""!=(s=r.text().trim())?'<span class="entry-excerpt excerpt">'+s.substr(0,a)+"…</span>":""):o="",o}function getPostComments(t,e,a,s,o){var r=t[e].author[0].name.$t,n=t[e].author[0].gd$image.src.replace("/s113","/s72-c").replace("/s220","/s72-c");return(n.match("//img1.blogblog.com/img/blank.gif")||n.match("//img1.blogblog.com/img/b16-rounded.gif"))&&(n="//1.bp.blogspot.com/-QN2lgvtYZco/YN3mUSryAVI/AAAAAAAAADs/KrR-etCcvUMcPl06jopTs9pzq59IAXhMQCLcBGAsYHQ/w72-h72-p-k-no-nu/avatar.jpg"),'<div class="cmm1-item item-'+e+'"><a class="entry-inner" href="'+a+'" title="'+r+'"><span class="entry-thumbnail cmm-avatar"><span class="thumbnail" data-src="'+n+'"></span></span><div class="entry-header"><h2 class="entry-title cmm-title">'+r+'</h2><p class="cmm-snippet excerpt">'+s+"</p></div></a></div>"}function getPostContent(t,e,a,s){var o="",r=(e.length,getPostLink(e,a)),n=getPostTitle(e,a),i=getPostAuthor(e,a),c=getPostDate(e,a),l=getPostImage(e,a),d=getPostImageType(l,a),p=getPostMeta(i,c),m=getPostTag(e,a);switch(t){case"mega":o+='<div class="post item-'+a+'"><a title="'+n+'" class="entry-thumbnail sz-3'+d+'" href="'+r+'"><span class="thumbnail" data-src="'+l+'"></span></a><div class="entry-header"><h2 class="entry-title"><a href="'+r+'" title="'+n+'">'+n+"</a></h2>"+p[1]+"</div></div>";break;case"ticker":o+='<div class="post item-'+a+(0==a?" active":"")+'"><h2 class="entry-title"><a href="'+r+'" title="'+n+'">'+n+"</a></h2></div>";break;case"trending":o+='<div class="post item-'+a+'"><a title="'+n+'" class="entry-thumbnail sz-2'+d+'" href="'+r+'"><span class="thumbnail" data-src="'+l+'"></span>'+m[1]+'</a><div class="entry-header"><h2 class="entry-title"><a href="'+r+'" title="'+n+'">'+n+"</a></h2>"+p[0]+"</div></div>";break;case"side":o+='<div class="post item-'+a+'"><a title="'+n+'" class="entry-thumbnail sz-4'+d+'" href="'+r+'"><span class="thumbnail" data-src="'+l+'"></span></a><div class="entry-header"><h2 class="entry-title"><a href="'+r+'" title="'+n+'">'+n+"</a></h2>"+p[1]+"</div></div>";break;case"related":a!=s-1&&(o+='<div class="post item-'+a+'"><a title="'+n+'" class="entry-thumbnail sz-3'+d+'" href="'+r+'"><span class="thumbnail" data-src="'+l+'"></span>'+m[1]+'</a><div class="entry-header"><h2 class="entry-title"><a href="'+r+'" title="'+n+'">'+n+"</a></h2>"+p[1]+"</div></div>");break;case"comments":o+=getPostComments(e,a,r,n)}return o}function getRecentPostsData(t,e,a){return $.ajax({url:getFeedUrl(t,e,"recent"),type:"GET",async:!1,dataType:"json",cache:!0,success:function(t){return t}}).responseJSON}function getPosts(t,e,a,s,o){s=0!=s?s:"unlabeled",$.ajax({url:getFeedUrl(e,a,s),type:"GET",dataType:"json",cache:!0,beforeSend:function(a){switch(e){case"mega":t.append('<div class="ul mega-items on-load">'+beforeLoader()+"</div>").addClass("loaded");break;case"ticker":case"trending":case"side":case"comments":case"related":t.html(beforeLoader()).parent().addClass("type-"+e)}},success:function(r){var n="";switch(e){case"mega":n='<div class="ul mega-items">';break;case"ticker":n='<div class="pbt-ticker ticker-items">';break;case"trending":n='<div class="trending-items">';break;case"side":n='<div class="side-items">';break;case"comments":n='<div class="cmm1-items">';break;case"related":n='<div class="related-items">'}var i=r.feed.entry;if(i){if("related"==e){1==i.length&&"recent"!=s&&(i=(r=getRecentPostsData(e,a)).feed.entry);for(let t=0;t<i.length;t++)if(1!=i.length&&getPostID(i,t)==o){i.splice(t,1);break}}for(let t=0,s=i;t<s.length;t++)n+=getPostContent(e,s,t,a)}else switch(e){case"mega":n='<div class="'+("mega"==e?"ul ":"")+'mega-items no-items">'+msgError()+"</div>";break;default:n=msgError()}switch(e){case"mega":n+="</div>",t.addClass(e).find(".mega-items").replaceWith(n);break;case"ticker":n+="</div>",t.html(n).pbtTicker();break;default:n+="</div>",t.html(n)}switch(e){case"mega":t.find("span.thumbnail").pbtLazy({onScroll:!1});break;default:t.find("span.thumbnail").pbtLazy()}},error:function(){switch(e){case"mega":t.find(".mega-items").replaceWith('<div class="ul mega-items no-items">'+msgError()+"</div>");break;default:t.html(msgError())}}})}function getMega(t,e,a,s){"mega"==e?getPosts(t,e,a,s):t.append('<div class="ul mega-items no-items">'+msgError()+"</div>").addClass("loaded")}function getTicker(t,e,a,s){if("ticker"==e)return getPosts(t,e,a,s);t.html(msgError())}function getTrending(t,e,a,s){if("trending"==e)return getPosts(t,e,a,s);t.html(msgError())}function getWidget(t,e,a,s,o){o.match("getposts")&&("side"==e||"comments"==e?getPosts(t,e,a,s):t.html(msgError()))}function getRelated(t,e,a,s,o){"related"==e?getPosts(t,e,a,s,o):t.html(msgError())}function disqusComments(t){var e=document.createElement("script");e.type="text/javascript",e.async=!0,e.src="//"+t+".disqus.com/blogger_item.js",document.getElementsByTagName("head")[0].appendChild(e)}function beautiAvatar(t){$(t).attr("src",function(t,e,a){return a="//1.bp.blogspot.com/-QN2lgvtYZco/YN3mUSryAVI/AAAAAAAAADs/KrR-etCcvUMcPl06jopTs9pzq59IAXhMQCLcBGAsYHQ/s35/avatar.jpg",e=(e=(e=e.replace("//resources.blogblog.com/img/blank.gif",a)).replace("//lh3.googleusercontent.com/zFdxGE77vvD2w5xHy6jkVuElKv-U9_9qLkRYK8OnbDeJPtjSZ82UPq5w6hJ-SA=s35",a)).replace("/s35","/s39")})}function pbtFixedSidebar(t){$(t).each(function(t,e){1==pbt.fixedSidebar&&(25,e=1==pbt.fixedMenu?$(".header-inner").height()+25:25,$(this).theiaStickySidebar({containerSelector:"#content-wrapper > .container",additionalMarginTop:e,additionalMarginBottom:25}))})}viewAllText="undefined"!=typeof viewAllText?viewAllText:pbt.viewAll,$("#buzzspot-pro-main-menu").pbtMenu().find(".widget").addClass("show-menu"),$("#main-search-wrap").each(function(){var t=$(this),e=$(window),a=$(".header-items");$(".show-search").click(function(){$("body").addClass("search-active"),t.fadeIn(170).find("input").focus()}),$(".search-close").click(function(){$("body").removeClass("search-active"),t.fadeOut(170).find("input").blur().val("")}),e.on("load resize",function(t,s){e.width()>980?(t=a.outerWidth(),s=$("#main-logo").outerWidth(),a.attr("style","--search-width:"+(t-(s+28))+"px")):a.attr("style","--search-width:100%")})}),$("html").each(function(){var t=$(this),e=localStorage.darkMode;1!=pbt.darkMode&&0!=pbt.userDarkMode&&("true"==e&&(t.addClass("is-dark"),darkModeLogo(e)),$(".darkmode-toggle").click(function(){$btn=$(this),$btn.hasClass("dark-on")?$btn.removeClass("dark-on").addClass("dark-off"):$btn.removeClass("dark-off").addClass("dark-on"),t.toggleClass("is-dark"),e="true"!=e?"true":"false",localStorage.darkMode=e,darkModeLogo(e)}))}),$(".dark-logo").each(function(){1==pbt.darkMode&&darkModeLogo("true")}),$("#ticker .PopularPosts .widget-content").pbtTicker(),$(".blog1-title a.title-link, .related-title a.title-link").each(function(){""!=viewAllText.trim()&&$(this).html(viewAllText)}),$(".pbt-section .social-icons a").each(function(t){var e=$(this),a=e.attr("href").split("#"),s=e.data("side");a[1]&&1==s&&""!=(t=a[1].trim())&&e.append('<span class="text">'+t+"</span>"),e.attr("href",a[0].trim())}),$(".MailChimp .widget-content").each(function(t,e){var a=$(this),s=a.data("shortcode");s&&(t=getAttr(s,"title"),e=getAttr(s,"text"),0!=t&&a.find(".mailchimp-title").text(t),0!=e&&a.find(".mailchimp-text").text(e))}),$(".post-body a").each(function(){var t=$(this),e=t.text(),a=e.toLowerCase(),s=getAttr(e,"text");a.match("getbutton")&&0!=s&&(t.replaceText(/([^{\}]+(?=}))/g,"<em>$1</em>"),t.find("em").replaceText("$","%s"),t.each(function(){var t=$(this),e=t.text(),a=getAttr(e,"text"),s=getAttr(e,"icon"),o=getAttr(e,"color"),r=getAttr(e,"size"),n=getAttr(e,"info"),i=t.parent().attr("style");t.addClass(0!=r?"button btn x2":"button btn").text(a.replace("%s","$")),i&&i.match("center")&&t.addClass("is-c"),0!=n?(t.addClass(0!=s?"x2 "+s:"x2"),t.append('<span class="btn-info">'+n.replace("%s","$")+"</span>")):0!=s&&t.addClass(s),0!=o&&t.addClass("color").attr("style","background:"+o+";")}))}),$(".post-body b").each(function(){var t=$(this),e=t.text(),a=e.toLowerCase().trim();a.match(/(?:\$ads\=\{1\})/g)&&t.replaceWith('<div id="buzzspot-pro-new-before-ad"/>'),a.match(/(?:\$ads\=\{2\})/g)&&t.replaceWith('<div id="buzzspot-pro-new-after-ad"/>'),a.match("{gettoc}")&&(e=0!=(e=getAttr(e,"title"))?e:"Table of Contents",t.replaceWith('<div class="pbt-toc-wrap"><div class="pbt-toc-inner"><button class="pbt-toc-title" aria-label="'+e+'"><span class="pbt-toc-title-text">'+e+'</span></button><ol id="pbt-toc"></ol></div></div>'),$(".pbt-toc-title").click(function(){$(this).toggleClass("is-expanded"),$("#pbt-toc").slideToggle(170)}),$("#pbt-toc").toc({content:"#post-body",headings:"h2,h3,h4"}),$("#pbt-toc li a").each(function(){var t=$(this);t.click(function(e){return e.preventDefault(),$("html,body").animate({scrollTop:$(t.attr("href")).offset().top-20},500),!1})})),a.match("{contactform}")&&(t.replaceWith('<div class="contact-form-widget"/>'),$("#post-body .contact-form-widget").append($("#ContactForm1 .contact-form-form"))),a.match("{leftsidebar}")&&($("body").addClass("is-left"),t.remove()),a.match("{rightsidebar}")&&($("body").addClass("is-right").removeClass("is-left"),t.remove()),a.match("{fullwidth}")&&($("body").addClass("no-sidebar"),t.remove())}),$("#buzzspot-pro-new-before-ad").each(function(){var t=$(this);t.length&&$("#before-ad").appendTo(t)}),$("#buzzspot-pro-new-after-ad").each(function(){var t=$(this);t.length&&$("#after-ad").appendTo(t)}),$("#buzzspot-pro-main-before-ad .widget").each(function(){var t=$(this),e=t.parent();t.length&&t.appendTo($("#before-ad")),e.remove(),caEmpty()}),$("#buzzspot-pro-main-after-ad .widget").each(function(){var t=$(this),e=t.parent();t.length&&t.appendTo($("#after-ad")),e.remove(),caEmpty()}),$("#buzzspot-pro-post-footer-ads .widget").each(function(){var t=$(this),e=t.parent();t.length&&t.appendTo($("#post-footer-ads")),e.remove()}),$(".post-body blockquote").each(function(){var t=$(this),e=t.text().toLowerCase().trim(),a=t.html();if(e.match("{alertsuccess}")){var s=a.replace("{alertSuccess}","");t.replaceWith('<div class="alert-message alert-success">'+s+"</div>")}if(e.match("{alertinfo}")){s=a.replace("{alertInfo}","");t.replaceWith('<div class="alert-message alert-info">'+s+"</div>")}if(e.match("{alertwarning}")){s=a.replace("{alertWarning}","");t.replaceWith('<div class="alert-message alert-warning">'+s+"</div>")}if(e.match("{alerterror}")){s=a.replace("{alertError}","");t.replaceWith('<div class="alert-message alert-error">'+s+"</div>")}if(e.match("{codebox}")){s=a.replace("{codeBox}","");t.replaceWith('<pre class="code-box">'+s+"</pre>")}}),$(".post-share .pbt-window").click(function(t){t.preventDefault();var e=$(this),a=e.data("url"),s=e.data("width"),o=e.data("height");window.open(a,"_blank","scrollbars=yes,resizable=yes,toolbar=0,width="+s+",height="+o+",top=50,left=50").focus()}),$(".post-share .show-more .btn, .share-toggle, .hide-modal, #share-overlay").click(function(t){t.preventDefault(),$("body").toggleClass("share-active")}),$(".about-author .author-text").each(function(){var t=$(this),e=t.find("a");e.length&&(e.each(function(){var t=$(this),e=t.text().trim(),a=t.attr("href");t.replaceWith('<li class="'+e+'"><a class="fa-'+e+'" href="'+a+'" title="'+e+'" rel="noopener noreferrer" target="_blank"/></li>')}),t.parent().append('<ul class="author-links social sc-a"></ul>'),t.find("li").appendTo(t.parent().find(".author-links")))}),$(".main-nav li.mega-menu").each(function(t,e){var a=$(this),s=a.find("a").data("shortcode");s&&(0!=(t=getAttr(s,"label"))&&(e="recent"==t?"/search":"/search/label/"+t,a.children("a").attr("href",e)),a.mouseenter(function(){a.hasClass("loaded")||getMega(a,"mega",5,t)}))}),$("#ticker .HTML .widget-content").each(function(t,e){var a=$(this),s=$(window),o=a.data("shortcode");o&&(t=getAttr(o,"results"),e=getAttr(o,"label"),s.on("load resize scroll",function o(){s.scrollTop()+s.height()>=a.offset().top&&(s.off("load resize scroll",o),getTicker(a,"ticker",t,e))}).trigger("scroll"))}),$("#trending .HTML .widget-content").each(function(t){var e=$(this),a=$(window),s=e.data("shortcode");s&&(t=getAttr(s,"label"),a.on("load resize scroll",function s(){a.scrollTop()+a.height()>=e.offset().top&&(a.off("load resize scroll",s),getTrending(e,"trending",4,t))}).trigger("scroll"))}),$(".pbt-section .HTML .widget-content").each(function(t,e,a,s){var o=$(this),r=$(window),n=o.data("shortcode");n&&(t=n.toLowerCase(),e=getAttr(n,"results"),a=getAttr(n,"label"),s="posts"!=(s=0!=(s=getAttr(n,"type"))?s:"side")?s:"side",r.on("load resize scroll",function n(){r.scrollTop()+r.height()>=o.offset().top&&(r.off("load resize scroll",n),getWidget(o,s,e,a,t))}).trigger("scroll"))}),$("#buzzspot-pro-related-posts .HTML").each(function(t,e){var a=$(this).data("shortcode");if(a){function s(){return t=getAttr(a,"results"),e=getAttr(a,"label"),[t,e]}$("#related-wrap").each(function(t,e,a,o){var r=$(this),n=r.find(".related-tag"),i=$(window),c=r.find(".related-content"),l=s();t=0!=l[0]?Number(l[0])+1:4,e=0!=l[1]?l[1]:n.data("label"),a=n.data("id"),0!=l[1]&&(o="recent"==e?"/search":"/search/label/"+e,r.find(".related-title .title-link").attr("href",o)),i.on("load resize scroll",function s(){i.scrollTop()+i.height()>=c.offset().top&&(i.off("load resize scroll",s),getRelated(c,"related",t,e,a),$("#buzzspot-pro-related-posts").remove())}).trigger("scroll")})}}),$(".buzzspot-pro-blog-post-comments").each(function(){var t=$(this),e=t.data("shortcode"),a=getAttr(e,"type"),s="comments-system-"+a,o=t.find("#top-continue .comment-reply");switch(a){case"disqus":var r=getAttr(e,"shortname");0!=r&&(disqus_shortname=r),disqusComments(disqus_shortname),t.addClass(s+" is-visible");break;case"facebook":var n=getAttr(e,"lang"),i=0!=n?"https://connect.facebook.net/"+n+"/all.js#xfbml=1&version=v11.0":"https://connect.facebook.net/en_US/sdk.js#xfbml=1&version=v11.0";$("head").append('<script async="async" defer="defer" crossorigin="anonymous" src="'+i+'"/>'),t.addClass(s).find("#comments").html('<div class="fb-comments" data-width="100%" data-href="'+disqus_blogger_current_url+'" order_by="time" data-numposts="5" data-lazy="true"></div>'),t.addClass("is-visible");break;case"hide":t.addClass("is-hidden");break;default:t.addClass("comments-system-blogger is-visible"),o.addClass("btn"),beautiAvatar(".avatar-image-container img")}var c=t.find(".comments .comment-reply"),l=t.find(".comments #top-continue"),d=t.find("#top-ce.comment-replybox-thread");c.click(function(t){t.preventDefault(),l.show(),d.hide()}),l.click(function(t){t.preventDefault(),l.hide(),d.show()})}),$(function(){$(".entry-thumbnail .thumbnail,.entry-avatar .avatar").not(".pbt-lazy").pbtLazy(),$(".mobile-logo").each(function(){var t=$(this),e=$(".main-logo a").clone();e.find("h1").remove(),e.appendTo(t)}),$("#mobile-menu").each(function(){var t=$(this),e=$(".main-nav").clone();e.attr("class","mobile-nav").attr("id","mobile-nav"),e.find(".mega-menu > .ul").remove(),e.find(".has-sub > a").after('<button class="submenu-toggle btn" aria-label="expand"/>'),e.find(".mega-menu").removeAttr("class").children(".submenu-toggle").remove(),e.find(".mega-menu > a").each(function(t,e){var a=$(this),s=a.data("shortcode");s&&0!=(t=getAttr(s,"label"))&&(e="recent"==t?"/search":"/search/label/"+t,a.attr("href",e))}),e.appendTo(t),$(".mobile-menu-toggle, .hide-mobile-menu, #overlay").click(function(){$("body").toggleClass("nav-active")}),$(".mobile-menu .submenu-toggle").click(function(){var t=$(this);t.parent().hasClass("expanded")?t.parent().removeClass("expanded").children(".sub-menu").slideToggle(170):t.parent().addClass("expanded").children(".sub-menu").slideToggle(170)})}),$(".mm-footer").each(function(){var t=$(this),e=$("#buzzspot-pro-about-section ul.social-icons"),a=$("#footer-menu ul.link-list"),s=!!e.length&&e.clone();0!=s&&(s.removeClass("sb-h").addClass("sc-a"),t.append(s)),$m=!!a.length&&a.clone(),0!=$m&&t.append($m)}),$(".header-inner").each(function(){var t=$(this);if(1==pbt.fixedMenu&&t.length>0){var e=$(document).scrollTop(),a=t.offset().top,s=t.height(),o=a+s+s;$(window).scroll(function(s,r){s=$(document).scrollTop(),a=t.offset().top,r=$(".main-header").offset().top+1,s>o?t.addClass("is-fixed"):a<=r&&t.removeClass("is-fixed").removeClass("show"),s<e?setTimeout(function(){a>=r&&t.addClass("show")},170):t.removeClass("show"),e=s})}}),pbtFixedSidebar("#main-wrapper, #sidebar-wrapper"),$("#post-body iframe").each(function(){var t=$(this);t.attr("src").match("www.youtube.com")&&t.wrap('<div class="youtube-video"/>')}),$("p.comment-content").each(function(){var t=$(this);t.replaceText(/(https:\/\/\S+(\.png|\.jpeg|\.jpg|\.gif))/g,'<img src="$1"/>'),t.replaceText(/(?:https:\/\/)?(?:www\.)?(?:youtube\.com)\/(?:watch\?v=)?(.+)/g,'<div class="youtube-video"><iframe id="youtube" width="100%" height="358" src="https://www.youtube.com/embed/$1" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>')}),$("#buzzspot-pro-load-more-link").each(function(){var t=$(this),e=t.data("load");e&&t.show(),t.click(function(a){a.preventDefault(),t.hide(),$.ajax({url:e,success:function(a){var s=$(a).find(".blog-posts");s.find(".post").addClass("fadeInUp"),$(".blog-posts").append(s.html()),(e=$(a).find("#buzzspot-pro-load-more-link").data("load"))?t.show():(t.hide(),$("#blog-pager .no-more").addClass("show"))},beforeSend:function(){$("#blog-pager .loading").show()},complete:function(){$("#blog-pager .loading").hide(),$(".blog-posts .post .thumbnail").not(".pbt-lazy").pbtLazy(),pbtFixedSidebar("#main-wrapper, #sidebar-wrapper")}})})}),$("#buzzspot-pro-cookie-consent").each(function(){var t=$(this),e=t.find(".widget.Text").data("shortcode"),a=t.find(".consent-button");t.length>0&&(e&&(ok=getAttr(e,"ok"),days=getAttr(e,"days"),0!=ok&&a.text(ok),days=0!=days?Number(days):7),"1"!==$.cookie("buzzspot_pro_cookie_consent")&&(t.css("display","block"),$(window).on("load",function(){t.addClass("is-visible")})),a.off("click").click(function(e){e.preventDefault(),e.stopPropagation(),$.cookie("buzzspot_pro_cookie_consent","1",{expires:days,path:"/"}),t.removeClass("is-visible"),setTimeout(function(){t.css("display","none")},500)}),cookieChoices={})}),$("#back-top").each(function(){var t=$(this);$(window).on("scroll",function(){$(this).scrollTop()>=100?t.addClass("show"):t.removeClass("show"),t.offset().top>=$("#footer-wrapper").offset().top-34?t.addClass("on-footer"):t.removeClass("on-footer")}),t.click(function(t){t.preventDefault(),$("html, body").animate({scrollTop:0},500)})})});
//]]>
</script>
<!-- Blogger Scripts -->
</body>
</html>
