# Standford-Encyclopedy-of-Philosophy

Download the article content of a entry in SEP with link of the entry

## What I need

You need the folowing librarys instaled via pip:

requests
validators

## Also need:

lxml with html

## Usage:

python sep.py \<standford entry link\>

## Results:

The script puts the content of the article in a sigle file named out.html. Is html raw without header or body content, only the \<div\> section with the article alone.

## What I cand do with this?

You can convert the html file to other formats vìa <b>pandoc</b>. Nice results with pdf latex output format. If you can't convert use xelatex engine.
