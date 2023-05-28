# terminal-timer User Guide

## Table of Contents

- Introduction
- Installation
- Usage
  - Options
  - Examples

## Introduction

terminal-timer is a simple command-line tool that allows you to display a countdown timer on your terminal. It provides the option to display the timer using a 7-segment representation or a regular string format.

## Installation

To use terminal-timer, follow these steps:

1. Clone the MyTimer repository from GitHub:
`git clone https://github.com/elimelt/terminal-timer.git`

2. Change directories to the terminal-timer directory
`cd terminal-timer`

3. You're ready to use terminal-timer!

## Usage

To use terminal-timer, run the `timer.py` script with the desired options. Here are the available options:

### Options

- `-h, --help`: Display the help message and usage information.
- `-d, --display`: Choose the display mode. Use `string` for a regular string format (default) or `segment` for a 7-segment representation.
- `-H, --hours`: Set the number of hours for the countdown timer (default: 0).
- `-M, --minutes`: Set the number of minutes for the countdown timer (default: 0).
- `-S, --seconds`: Set the number of seconds for the countdown timer (default: 0).

### Examples

- Display the countdown timer in regular string format for 1 hour, 30 minutes, and 0 seconds:
`python timer.py -H 1 -M 30`

- Display the countdown timer for 10 seconds using the default settings:
python timer.py -S 10

- Display a seven segment digital clock esq view of a countdown timer for 24 hours:
python timer.py -H 24


The possibilities are endless! 

Please feel free to submit an issue with any features you'd like to see. I'd be happy to implement them.

