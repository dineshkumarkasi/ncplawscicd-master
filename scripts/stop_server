#!/bin/bash

if systemctl is-active --quiet httpd; then
    echo "Stopping Apache (httpd)..."
    sudo systemctl stop httpd
else
    echo "Apache (httpd) is not running."
fi

