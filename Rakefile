

file 'hello.o' => 'hello.c' do
	sh 'cc -c -o hello.o hello.c'
end
file 'hello' => 'hello.o' do
	sh 'cc -o hello hello.o'
end

