export PATH := $(shell pwd)/node_modules/.bin:$(PATH)
SHELL := /bin/bash


publishPatch:
	npm version patch
	npm publish --access public

