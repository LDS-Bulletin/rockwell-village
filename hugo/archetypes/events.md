+++
date = '{{ .Date }}'
endDate = ''
startTime = ''
endTime = ''
location = ''
title = '{{ .File.ContentBaseName | replaceRE "[-_]+" " " | title }}'
+++
