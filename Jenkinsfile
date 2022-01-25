properties([pipelineTriggers([pollSCM('* * * * 30')])])
node{
    stage("1"){
        git branch:"main", url: "https://github.com/Hillelg-cloud/MySoftware.git"
        bat "C:/Users/il_ro/AppData/Local/Programs/Python/Python310/python.exe Newbutton.py"
        bat "C:/Users/il_ro/AppData/Local/Programs/Python/Python310/python.exe NewScreen.py"
    }
}
