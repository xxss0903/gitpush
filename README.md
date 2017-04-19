# gitpush
git auto push sh

## add gitpush
* change gitpush.sh to execuable file: $chmod +x gitpush.sh
* move gitpush.sh to ~/.ssh directory
* add alias to you shell environment: 
$vim ~/.shrc
add "alias gitpush='bash ~/.ssh'" to shrc tail
* source you .shrc file: $source ~/.shrc


## useage
* $cd project_directory
* $gitpush
* $y
* add commit comment
* if directory is not initialized, then you need add remote url


