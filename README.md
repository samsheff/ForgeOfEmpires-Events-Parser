# Forge of Empires Events Parser
A shell script for extracting Base64 Encoded Analytics Events from the Forge of Empires web client

## Background
I was curious what analytics events were collected by the Forge of Empires web client, and additionally was curious what my footprint looked like. Thus, I made a system for collecting these anayltics events for myself.

## Setup
1. Install the Network Recorder plugin for Chrome, available here: https://chrome.google.com/webstore/detail/network-record/ihbkogfblhfbnompooimhejpkidoipcl
2. Open the client and start recording by clicking the addon's icon
3. When finished, stop recording and save the file as history.json in the same directory as the shell script.

## Extracting Events
1. Install jq: https://stedolan.github.io/jq/
2. run `parse_events.sh` and watch the decoded analytics events appear in your console.

## Future
I'll be working on a way to automatically add these events to a database.
