## Can not enable VSCode Intellisense when working with Unity C# project
* If you use unity project `gitignore` template, remember to remove **.sln** from `gitignore`, otherwise VSCode couldn't fetch project setting thus no Intellisense enabled.

## Install venv in WSL
If you install in Windowns part (/mnt/XXX), an error will occur.
`Error: Command '['/mnt/e/joseph/code/python/venv2/bin/python3', '-Im', 'ensurepip', '--upgrade', '--default-pip']' returned non-zero exit status 1.`

Switch to Linux part by `cd` and `python3 -m venv venv` again should fix the problem

