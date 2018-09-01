run:
	rm -rf node_modules modules
	npm i ava@next
	./node_modules/.bin/ava test.js
	mv node_modules modules
	env NODE_PATH=$(PWD)/modules node ./modules/.bin/ava ./test.js
