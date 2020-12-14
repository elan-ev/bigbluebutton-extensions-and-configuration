# BigBlueButton: Extensions and Configuration

This repository contains a list of non-official BigBlueButton extensions, configurations and hacks maintained by the community

## Integrations

- [Stud.IP Meetings Plugin](https://github.com/virtUOS/studip-meeting)
    - Use Stud.IP as front-end for BigBlueButton
    - Integrates nicely in courses created within that LMS
    - Lecturers can control their online conferencing rooms
    - Interacts with Opencast for recordings
- [Opencast Integration](https://github.com/elan-ev/opencast-bigbluebutton-integration)
    - Offload recordings (processing, publishing) to Opencast

## Configuration

- [Restrict Logging](https://github.com/virtUOS/bigbluebutton-ansible/blob/master/roles/bigbluebutton/tasks/logging.yml)
    - Log only what's necessary
    - Privacy friendly
    - Don't include chat messages, … in logs
