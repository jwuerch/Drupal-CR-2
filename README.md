# Ceasar's Cipher - April 22, 2016

## Description

The Ceasar's Cipher module allows a user to put in 3 inputs: a phrase, a shift value and a shift direction. The phrase needs to be either
spaces, punctuation (!?,.-) or letters. If it's none of these things, you will get an error. The shift value tells you how far each
letter will shift from its current place in the alphabet, and the direction tells you whether it will go left or right. All punctuation will stay.

Example:

* Phrase: hi you!
* Shift Direction: left
* Shift Value: 1

* Output: gh xpt!

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [MAMP]

## Installation

* Git clone `https://github.com/jwuerch/Druapl-CR-2.git`.
* Change into the new directory.
* Start up mamp and point servers to main directory.
* Go to localhost:8888/phpmyadmin in browser and import `drupal_cr_2.sql.zip` DB found in Drupal-CR-1/sites/DB-Backup.
* Create DB username `admin3` with password `admin3`.
* Go to localhost:8888 to view Drupal project.
* Log-in as administrator with username `admin3` and password `admin3`.

## Databases Used
* `drupal_cr_2`

## Usernames and Passwords
* DB: `admin3:admin3`
* Drupal site maintenance account: `admin3:admin3`

## Running / Development

* Visit your app at [http://localhost:8888](http://localhost:8888).

### Deploying

All you need to deploy is to visit localhost:8888. The app is currently not hosted.

##License

This software is licensed under the MIT license.
Copyright (c) 2016 _**Jason Wuerch**_.
