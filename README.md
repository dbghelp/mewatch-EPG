# mewatch-EPG

## Overview

This repository contains the XML EPG (Electronic Program Guide) for mewatch channels. The EPG provides a schedule of the current and upcoming TV programs, enabling users to easily see what's on and plan their viewing.

## Features

- XML formatted EPG for mewatch channels
- Up-to-date information on channel programming
- Easy integration with various applications and services

## Usage

To use the EPG data, you can fetch the XML file from this repository and parse it in your application to display the program schedule.

In your M3U8 playlist, 

1. Change your url-tvg to "https://raw.githubusercontent.com/dbghelp/mewatch-EPG/refs/heads/main/mewatch.xml":

```#EXTM3U url-tvg="https://raw.githubusercontent.com/dbghelp/mewatch-EPG/refs/heads/main/mewatch.xml" refresh="3600"```

2. Change your tvg-id for the respective channels:
  
| tvg-id | Channel Name      |
|------------|--------------------|
| 97098      | Channel 5         |
| 97104      | Channel 8         |
| 97129      | Channel U         |
| 97084      | Suria             |
| 97096      | Vasantham         |
| 97072      | CNA               |
| 98200      | SPL CH01          |
| 98201      | SPL CH02          |
| 158965     | NOW 80s           |
| 158964     | NOW 70s           |
| 158963     | NOW Rock          |
| 158962     | TRACE Urban       |
| 227348     | ROCK Entertainment|
| 227349     | ROCK Action       |
| 158961     | Global Trekker    |
| 242030     | Animax            |
| 382872     | CinemaWorld       |
| 97073      | LIVE 1            |
| 97078      | LIVE 2            |
| 98202      | LIVE 5            |
