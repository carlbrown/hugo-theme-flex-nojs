+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = '{{ .Date }}'
draft = true
categories = [
	"Default"
]
image = '{{ .File.ContentBaseName | title | lower }}.png'
published = false
tags = [
	"default",
	"default2"
]
url = '/{{ dateFormat "06/01/02" .Date }}/{{ .File.ContentBaseName | title | lower }}.html'
+++
