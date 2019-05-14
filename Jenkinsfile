def changes = currentBuild.changeSets[0].collect {"${it.commitId}: ${it.msg}"} .join("\n")
println changes.size()
println changes
