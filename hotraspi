#!/usr/bin/env bash
printf "CPU Temperature  =>  $(($(cat /sys/class/thermal/thermal_zone0/temp)/1000))'C\n"
printf "GPU Temperature  =>  $(vcgencmd measure_temp | cut -c 6,7)'C\n"
