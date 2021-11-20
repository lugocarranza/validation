build :
	hugo -D > /dev/null 2>&1

clean :
	rm -rf ./dist/ > /dev/null 2>&1
	
post : 
	hugo new posts/$(POST_NAME).md
	echo 'title: "$(POST_TITLE)"' > ./content/posts/$(POST_NAME).md
