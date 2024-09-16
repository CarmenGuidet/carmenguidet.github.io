---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
title: "Inicio"
description: "Experimenta las telecomunicaciones"
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#

widget1:
  title: "Comunicaciones clasicas"
  url: 'http://carmenguidet.github.io/conoce/comunicaciones'
  image: http://carmenguidet.github.io/images/comunicaciones.jpg 
  text: 'Aqui descubriras que es lo que nos perimite comunicarnos a largas distancias.'
widget2:
  title: "Electronica"
  url: 'http://carmenguidet.github.io/conoce/electronica'
  image: http://carmenguidet.github.io/images/electronica.jpg
  text: 'Nos permite crear ciudades inteligentes, robots y MUCHO MÁS.'
widget3:
  title: "Telematica"
  url: 'http://carmenguidet.github.io/conoce/redes'
  image: http://carmenguidet.github.io/images/telematica.jpg
  text: 'Nos permite mantenernos seguros en la red, encriptar información.'
widget4:
  title: "Multimedia"
  url: 'http://carmenguidet.github.io/conoce/multimedia'
  image: http://carmenguidet.github.io/images/multimedia.jpg
  text: 'Realidad aumentada, inteligencia artificial.'


callforaction:
  url1: http://carmenguidet.github.io/experimenta/casa
  text1: Experimenta y crea desde casa 
  style1: alert
  url2: http://carmenguidet.github.io/experimenta/profesorado
  text2: Para profesorado
  style2: alert

permalink: /index.html

#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true

--- 