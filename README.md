
# clone the repository into the current directory in terminal
git clone https://github.com/kpiasecki/Hello-World.git

# change the active directory in the prompt to the newly cloned "Hello-World" directory
cd Hello-World

# compile the "Hello-World" project
mvn package

# run "Hello-World" project
java -cp target/Hello-World-1.0-SNAPSHOT.jar zut.wi.kpiasecki.hello.App
