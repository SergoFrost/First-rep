git reset HEAD~1 				// 	сбросить прошлый коммит оставить изменения. после ~ количество комитов
git reset --hard HEAD~1			// 	сбросить прошлый коммит удалить изменения
git stash apply					// 	применит стеш
git branch -D dev				// 	Удалить ветку локально 
git push origin :dev			//	Удалить ветку на сервере

git push --force origin dev 	//	пушнуть изменёные комиты
git rebase master				// 	подтянуть в свою ветку последние изменения из мастера
git mv McCoy.rb Mccoy.rb.tmp && git mv Mccoy.rb.tmp Mccoy.rb  		// переименовывание под виндой
git checkout -b newbranch		//	создание ветки


git clone -b dev ssh://git@code.akademos.com/repo.git

git fetch origin    //подтянуть свеживе ветки
