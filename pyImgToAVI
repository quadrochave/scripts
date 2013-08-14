#!/usr/bin/env python
# -*- coding: utf-8 -*-

# pyimg2avi 0.1  - Utilitario simples para conversão de sequência de imagens em um video avi
# Desenvolvido por Henrique Lopes Barone

import os

format = raw_input ('Formato da imagem: ')
fps = raw_input ('Taxa de quadros por segundo: ')
videoOut = raw_input ('Nome do vídeo: ')


os.system ('mencoder mf://*.' + format + ' -mf fps=' + fps + ':type=' + format + ' -ovc lavc \
    -lavcopts vcodec=mpeg4:mbd=2:trell -oac copy -o ' + videoOut + '.avi')
