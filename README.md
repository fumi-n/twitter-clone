#commnds

##git 

git add -A && git commit -a -m 'commits' && git diff HEAD^

#git diff --name-only HEAD^

##rails s

rails s -b $IP -p $PORT


##DB  


rails db:migrate


##add Column

rails g migration Addカラム名(最初大文字)Toテーブル名(最初大文字) カラム名:カラムのデータ型

rails db:migrate

validates :title, presence: true, length: { maximum: 255 }

rails g migration AddstatusTotasks status:string
rails g migration AddStatusToTasks status:string

##git branch
git branch
git branck dev

git checkout dev

git merge 



