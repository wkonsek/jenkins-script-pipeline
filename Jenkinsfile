node('master'){
	checkout scm
	echo "TEST!!! *** after tag"
	def tag = helpers.getGitTag()
	print tag
}
