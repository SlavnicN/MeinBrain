202304261737
Status: #idea
Tags: [[shortcut]] 

# Intellij Idea Shortcut

- shot action to do on error = Alt + Enter 
- cycle through errors = F2
- Open/close file explorer = Alt + 1
- Open recent file popup = ctrl + E



Try new shortcut:

let mapleader = " "
map <leader>a :action $SelectAll<CR>
map <leader>b :action GotoDeclaration<CR>
map <leader>c :action $Copy<CR>
map <leader>d :action EditorDuplicate<CR>
map <leader>e :action RecentFiles<CR>
map <leader>f :action Find<CR>
map <leader>g :action GotoLine<CR>
map <leader>h :action TypeHierarchy<CR>
map <leader>i :action ImplementMethods<CR>
map <leader>m :action EditorScrollToCenter<CR>
map <leader>n :action FileChooser.NewFolder<CR>
map <leader>o :action OverrideMethods<CR>
map <leader>p :action ParameterInfo<CR>
map <leader>q :action QuickJavaDoc<CR>
map <leader>r :action Replace<CR>
map <leader>s :action SaveAll<CR>
map <leader>t :action Vcs.UpdateProject<CR>
map <leader>u :action GotoSuperMethod<CR>
map <leader>v :action $Paste<CR>
map <leader>w :action EditorSelectWord<CR>
map <leader>x :action $Cut<CR>
map <leader>y :action EditorDeleteLine<CR>
map <leader>[ :action EditorCodeBlockStart<CR>
map <leader>] :action EditorCodeBlockEnd<CR>

---
# References
https://danidiaz.medium.com/configuring-ideavimrc-de16a4da0715
