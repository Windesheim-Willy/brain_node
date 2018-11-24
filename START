#!/bin/bash
set -e

case "$1" in
start)
  exec ./components/ros_master/START start
  exec ./components/brain/START start
  ;;
stop)
  exec ./components/ros_master/START stop
  exec ./components/brain/START stop
  ;;
restart)
  $0 stop
  $0 start
  ;;
*)
  echo "Usage: $0 {start|stop|status|restart}"
esac

exit 0
