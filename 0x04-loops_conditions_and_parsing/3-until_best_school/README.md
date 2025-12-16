#!/usr/bin/env bash
# This script displays "Best School" exactly 10 times using an until loop.
n=1
until [ $n -gt 10 ]; do
	echo "Best School"
	n=$((n + 1))
done
