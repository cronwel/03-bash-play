# Playcode.sh

## Purpose
***
Keep track of what gets updated when performing <code> apt-get update</code>.

## Commands
***
Performs the commands:
- runs <code>sudo apt-get udpate</code>.
- creates <code>update.txt</code> file with output of previous commands.

## Rationale
***
- Provides data to investigate or backtrack after an update in case something brakes.
- Updates can break code and want to backtrack to see when was the last time a program properly worked.
