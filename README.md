## Git算不算程序员的必备技能？ V2GL0G

更新时间：2026-09-15 06:37:57.919

3w2tyf.kvb1995.com
3owllo.kvb1993.com
现在dev分支工作已完成，现在我们切换到主分支master上，继续查看readme.txt内容如下：
2kvmq1.hothairybushes.com
Git算不算程序员的必备技能？
3oksr8.kvb1987.com
首先我们先来查看下readme.txt内容，接着添加内容77777777，如下：
2t26xm.hothairybushes.com
git branch查看分支，会列出所有的分支，当前分支前面会添加一个星号。然后我们在dev分支上继续做demo，比如我们现在在readme.txt再增加一行 7777777777777
3zca8c.inmolopez.com
3ypw4q.hoodamath2.com
git checkout dev
2ti74g.kvb1997.com
2pw7b9.kvb1989.com
git branch dev
35mszb.hoodamath2.com
41u1al.misturabela.com
2znejb.cdroutlet.com
git checkout 命令加上 –b参数表示创建并切换，相当于如下2条命令
37yjg7.ecvyksp.cn
4343ff.hothairybushes.com
2symg9.kvb1986.com
Git算不算程序员的必备技能？
3jai47.cdroutlet.com
3yr46e.hoodamath2.com
44hpvj.kvb1979.com
首先，我们来创建dev分支，然后切换到dev分支上。如下操作：
2yfg6j.cdroutlet.com
在 版本回填退里，你已经知道，每次提交，Git都把它们串成一条时间线，这条时间线就是一个分支。截止到目前，只有一条时间线，在Git里，这个分支叫主分支，即master分支。HEAD严格来说不是指向提交，而是指向master，master才是指向提交的，所以，HEAD指向的就是当前分支。
4hhgbj.kvb1993.com
3avzq4.kvb1979.com
3xsxd9.kvb1997.com
37oogh.inmolopez.com
3kj5m4.kvb1998.com
4gas4h.kvb1980.com
3vui27.kvb1982.com
4i1v20.kvb1987.com
3n4505.compasslandconsultants.com
3lwrkp.cdroutlet.com
3u5wkt.cdroutlet.com
2wjdjo.cdroutlet.com
六：创建与合并分支。
4dftb4.kvb1985.com
2wfg2l.misturabela.com
Git算不算程序员的必备技能？
3r46c7.ecvyksp.cn
3qt4w5.compasslandconsultants.com
3wed91.kvb1991.com
2o8lgh.ecvyksp.cn
接着在我本地目录下 生成testgit2目录了，如下所示：
3gril7.kvb1988.com
382o4h.kvb1983.com
3w8rsw.kvb1992.com
2rnbz2.kvb1986.com
384d2n.kvb1988.com
2z6xp9.compasslandconsultants.com
Git算不算程序员的必备技能？
3td8yd.inmolopez.com
48thnk.kvb1985.com
43f0ch.compasslandconsultants.com
2okt6b.hongyihualang.cn
3k7yps.hongyihualang.cn
2v0m6o.compasslandconsultants.com
3qf4pm.kvb1983.com
2wknfd.kvb1999.com
37t1n5.cdroutlet.com
2w0yvv.ecvyksp.cn
现在，远程库已经准备好了，下一步是使用命令git clone克隆一个本地库了。如下所示：
43vwy7.kvb1999.com
2ngbew.ecvyksp.cn
Git算不算程序员的必备技能？
3kixf0.kvb1988.com
如下，我们看到：
2s6dvy.compasslandconsultants.com
2tkzy5.misturabela.com
3jvlcf.cdroutlet.com
487lbi.compasslandconsultants.com
3emxzi.ecvyksp.cn
3jovis.kvb1993.com
3lofr4.kvb1979.com
Git算不算程序员的必备技能？
3xur9h.ecvyksp.cn
40p97v.kvb1982.com
3rt0xj.kvb1979.com
3dbx9h.misturabela.com
478txm.kvb1983.com
首先，登录github，创建一个新的仓库，名字叫testgit2.如下：
3rqggl.cdroutlet.com
47huua.kvb1985.com
3q898g.kvb1995.com
3u7rvy.hothairybushes.com
3iigd9.hongyihualang.cn
3lqjt4.cdroutlet.com
3l2g4y.kvb1988.com
337kgq.kvb1980.com
2p624d.compasslandconsultants.com
3shlc7.kvb1980.com
3aerra.cdroutlet.com
4epwgq.kvb1980.com
现在我们想，假如远程库有新的内容了，我想克隆到本地来 如何克隆呢？
2uguxp.hothairybushes.com
如何从远程库克隆？上面我们了解了先有本地库，后有远程库时候，如何关联远程库。
3mg8aa.compasslandconsultants.com
2vsnsp.cdroutlet.com
34rytg.kvb1983.com
把本地master分支的最新修改推送到github上了，现在你就拥有了真正的分布式版本库了。
36x5t5.kvb1993.com
git push origin master
3r2wje.kvb1992.com
2vlw7j.hothairybushes.com
2z7tcm.misturabela.com
2svh55.hoodamath2.com
2yxhom.hongyihualang.cn
3k6h3n.inmolopez.com
4145m9.kvb1978.com
453zb9.hongyihualang.cn
3mi86m.kvb1991.com
从现在起，只要本地作了提交，就可以通过如下命令：
3hjp6e.kvb1997.com
2ttacr.cdroutlet.com
3ytd8t.kvb1980.com
4dql4y.kvb1987.com
Git算不算程序员的必备技能？
3qxa7h.kvb1999.com
由于远程库是空的，我们第一次推送master分支时，加上了 –u参数，Git不但会把本地的master分支内容推送的远程新的master分支，还会把本地的master分支和远程的master分支关联起来，在以后的推送或者拉取时就可以简化命令。推送成功后，可以立刻在github页面中看到远程库的内容已经和本地一模一样了，上面的要输入github的用户名和密码如下所示：
36amoa.inmolopez.com
把本地库的内容推送到远程，使用 git push命令，实际上是把当前分支master推送到远程。
2qc58w.kvb1995.com
Git算不算程序员的必备技能？
2t8i68.kvb1979.com
2ugwzx.kvb1986.com
4enwni.kvb1999.com
31kf7g.kvb1989.com
2sn2m7.kvb1980.com
3iqzae.ecvyksp.cn
31ta6m.inmolopez.com
3r539e.hongyihualang.cn
2vkoz9.kvb1995.com
所有的如下：
4jbnfq.kvb1980.com
git remote add origin
40ebyv.kvb1991.com
3wmlzy.hothairybushes.com
现在，我们根据GitHub的提示，在本地的testgit仓库下运行命令：
3wdx3v.kvb1981.com
目前，在GitHub上的这个testgit仓库还是空的，GitHub告诉我们，可以从这个仓库克隆出新的仓库，也可以把一个已有的本地仓库与之关联，然后，把本地仓库的内容推送到GitHub仓库。
449if1.kvb1982.com
3pgyg8.hoodamath2.com
48p5uv.inmolopez.com
38m017.kvb1981.com
31n88r.kvb1998.com
3ot56z.kvb1996.com
Git算不算程序员的必备技能？
3t0whp.inmolopez.com
3nae3v.kvb1997.com
在Repository name填入testgit，其他保持默认设置，点击“Create repository”按钮，就成功地创建了一个新的Git仓库：
3j85w8.misturabela.com
3ccpxy.compasslandconsultants.com
2vq95c.hothairybushes.com
35jaar.kvb1983.com
3r3wco.ecvyksp.cn
3i87p0.compasslandconsultants.com
Git算不算程序员的必备技能？
3zsmq4.kvb1999.com
首先，登录github上，然后在右上角找到“create a new repo”创建一个新的仓库。如下：
41tfvw.kvb1991.com
现在的情景是：我们已经在本地创建了一个Git仓库后，又想在github创建一个Git仓库，并且希望这两个仓库进行远程同步，这样github的仓库可以作为备份，又可以其他人通过该仓库来协作。
2sy39c.inmolopez.com
如何添加远程库？
4a5kcu.kvb1987.com
3qak0y.kvb1981.com
497r3v.misturabela.com
3vw12z.kvb1980.com
2nn6cg.ecvyksp.cn
Git算不算程序员的必备技能？
3p0egg.kvb1995.com
点击 Add Key，你就应该可以看到已经添加的key。
3uef6i.kvb1999.com
30ilp8.kvb1979.com
3ppdvn.compasslandconsultants.com
30yq34.kvb1988.com
Git算不算程序员的必备技能？
3gwkzx.misturabela.com
3fdprr.hothairybushes.com
3n43fd.kvb1997.com
37a0io.kvb1998.com
第二步：登录github,打开” settings”中的SSH Keys页面，然后点击“Add SSH Key”,填上任意title，在Key文本框里黏贴id_rsa.pub文件的内容。
30lbh8.compasslandconsultants.com
id_rsa是私钥，不能泄露出去，id_rsa.pub是公钥，可以放心地告诉任何人。
3o48uf.kvb1983.com
3h3uex.ecvyksp.cn
3a1l4a.kvb1990.com
49ysa1.ecvyksp.cn
Git算不算程序员的必备技能？
34vpn7.kvb1998.com
41sze8.kvb1982.com
35gjji.cdroutlet.com
3q6z71.kvb1983.com
ssh-keygen -t rsa –C “youremail@example.com”, 由于我本地此前运行过一次，所以本地有，如下所示：
3ypf0s.hothairybushes.com
3xg6wu.kvb1983.com
3aclhk.kvb1980.com
37jdzc.hoodamath2.com
2qph8n.kvb1978.com
第一步：创建SSH Key。在用户主目录下，看看有没有.ssh目录，如果有，再看看这个目录下有没有id_rsa和id_rsa.pub这两个文件，如果有的话，直接跳过此如下命令，如果没有的话，打开命令行，输入如下命令：
3aid2v.ecvyksp.cn
4f4w32.kvb1985.com
在了解之前，先注册github账号，由于你的本地Git仓库和github仓库之间的传输是通过SSH加密的，所以需要一点设置：
4c3v8k.kvb1996.com
45hd9w.compasslandconsultants.com
五：远程仓库。
3f13ga.ecvyksp.cn
Git算不算程序员的必备技能？
3wkqxu.kvb1983.com
2rwg31.kvb1995.com
再来看看我们testgit目录，添加了3个文件了。如下所示：
440la1.ecvyksp.cn
Git算不算程序员的必备技能？
4f8tnk.kvb1990.com
可以使用如下命令 git checkout -- b.txt，如下所示：
4ilyyu.kvb1978.com
只要没有commit之前，如果我想在版本库中恢复此文件如何操作呢？
4egrfd.kvb1991.com
3411od.hothairybushes.com
480z11.kvb1990.com
Git算不算程序员的必备技能？
47rv77.inmolopez.com
2ydrrk.kvb1983.com
2tsskr.inmolopez.com
2q1ksn.kvb1987.com
如上：一般情况下，可以直接在文件目录中把文件删了，或者使用如上rm命令：rm b.txt ，如果我想彻底从版本库中删掉了此文件的话，可以再执行commit命令 提交掉，现在目录是这样的，
3vboqo.compasslandconsultants.com
3geveo.cdroutlet.com
49frpd.kvb1986.com
3elyyx.hothairybushes.com
Git算不算程序员的必备技能？
2srei3.hothairybushes.com
2vjvsp.inmolopez.com
335gdn.misturabela.com
假如我现在版本库testgit目录添加一个文件b.txt,然后提交。如下：
3qnngi.kvb1983.com
二：删除文件。
36xcyx.kvb1982.com
注意：命令git checkout -- readme.txt 中的 -- 很重要，如果没有 -- 的话，那么命令变成创建分支了。
45f35m.hongyihualang.cn
3wxyhs.kvb1995.com
2pacgh.ecvyksp.cn
Git算不算程序员的必备技能？
45cg8d.kvb1980.com
对于第二种情况，我想我们继续做demo来看下，假如现在我对readme.txt添加一行 内容为6666666666666，我git add 增加到暂存区后，接着添加内容7777777，我想通过撤销命令让其回到暂存区后的状态。如下所示：
34zu9k.kvb1998.com
380n1z.kvb1995.com
2.另外一种是readme.txt已经放入暂存区了，接着又作了修改，撤销修改就回到添加暂存区后的状态。
3qqsrd.compasslandconsultants.com
46lile.ecvyksp.cn
1.readme.txt自动修改后，还没有放到暂存区，使用 撤销修改就回到和版本库一模一样的状态。
36nawh.kvb1991.com
4gu49b.kvb1979.com
命令 git checkout --readme.txt 意思就是，把readme.txt文件在工作区做的修改全部撤销，这里有2种情况，如下：
46enqc.kvb1995.com
36fcv3.misturabela.com
40tpw4.kvb1982.com
Git算不算程序员的必备技能？
35593r.kvb1990.com
31ylnu.kvb1992.com
3dunwq.hoodamath2.com
2zmigz.hongyihualang.cn
2mbf1d.misturabela.com
2rgup6.hothairybushes.com
git checkout -- readme.txt,如下所示：
2wl37a.ecvyksp.cn
可以发现，Git会告诉你，git checkout -- file 可以丢弃工作区的修改，如下命令：
4893l8.kvb1987.com
2l0huy.misturabela.com
2wtnv9.misturabela.com
Git算不算程序员的必备技能？
2y3wxt.hoodamath2.com
但是现在我不想使用上面的2种方法，我想直接想使用撤销命令该如何操作呢？首先在做撤销之前，我们可以先用 git status 查看下当前的状态。如下所示：
491fp5.hothairybushes.com
3bgp8w.ecvyksp.cn
第二：我可以按以前的方法直接恢复到上一个版本。使用 git reset --hard HEAD^
2zr9g4.kvb1990.com
3pycxl.kvb1981.com
第一：如果我知道要删掉那些内容的话，直接手动更改去掉那些需要的文件，然后add添加到暂存区，最后commit掉。
3v64r6.hongyihualang.cn
4abjgy.kvb1991.com
32ytn5.kvb1996.com
33uhe7.kvb1981.com
2snrhw.kvb1996.com
在我未提交之前，我发现添加5555555555555内容有误，所以我得马上恢复以前的版本，现在我可以有如下几种方法可以做修改：
3eepvh.hongyihualang.cn
2v9mgz.kvb1997.com
Git算不算程序员的必备技能？
3n9j11.kvb1979.com
2parlr.compasslandconsultants.com
3o401h.cdroutlet.com
3frkkf.misturabela.com
424lv6.kvb1995.com
比如我现在在readme.txt文件里面增加一行 内容为555555555555，我们先通过命令查看如下：
3rb7kj.kvb1991.com
34hqyl.kvb1991.com
414l0h.kvb1995.com
一：撤销修改：
3j3wnz.kvb1997.com
3wvkyy.ecvyksp.cn
361sym.hoodamath2.com
32vndr.hothairybushes.com
3yr032.kvb1982.com
3mk8rh.kvb1996.com
四：Git撤销修改和删除文件操作。
3ghg3q.kvb1983.com
Git算不算程序员的必备技能？
3idmw7.hoodamath2.com
3eh3kj.kvb1995.com
3enbdu.kvb1999.com
306mrz.kvb1998.com
3yztau.kvb1999.com
接着我们可以使用git commit一次性提交到分支上，如下：
36nla7.inmolopez.com
2y99g6.hoodamath2.com
Git算不算程序员的必备技能？
40bu23.kvb1993.com
现在我们先使用git add 命令把2个文件都添加到暂存区中，再使用git status来查看下状态，如下：
2wc6ax.kvb1983.com
Git算不算程序员的必备技能？
2w5oox.inmolopez.com
我们在readme.txt再添加一行内容为4444444，接着在目录下新建一个文件为test.txt 内容为test，我们先用命令 git status来查看下状态，如下：
3m6fcx.kvb1992.com
3qkpq9.hothairybushes.com
4gvy4f.kvb1992.com
4j0yt6.kvb1996.com
3059ig.inmolopez.com
2u6j7k.hothairybushes.com
477n8c.kvb1998.com
33zmqk.hongyihualang.cn
我们继续使用demo来演示下：
460c2o.kvb1986.com
第二步：使用git commit提交更改，实际上就是把暂存区的所有内容提交到当前分支上。
3cxcvw.kvb1990.com
第一步：是使用 git add 把文件添加进去，实际上就是把文件添加到暂存区。
2rx7nj.inmolopez.com
我们前面说过使用Git提交文件到版本库有两步：
2yyywe.compasslandconsultants.com
406d7x.kvb1996.com
4ehl09.kvb1999.com
40sn68.hongyihualang.cn
3fy0g4.kvb1995.com
430e53.kvb1998.com
2r7qw5.kvb1986.com
2wy7c9.kvb1989.com
版本库(Repository)：工作区有一个隐藏目录.git,这个不属于工作区，这是版本库。其中版本库里面存了很多东西，其中最重要的就是stage(暂存区)，还有Git为我们自动创建了第一个分支master,以及指向master的一个指针HEAD。
40rx0e.hongyihualang.cn
3clyyu.misturabela.com
工作区：就是你在电脑上看到的目录，比如目录下testgit里的文件(.git隐藏目录版本库除外)。或者以后需要再新建的目录文件等等都属于工作区范畴。
2vqfqb.kvb1983.com
2w1e98.kvb1978.com
3zp3f5.kvb1981.com
2ry047.misturabela.com
3xrtxt.kvb1990.com
3ywdib.kvb1978.com
三：理解工作区与暂存区的区别？
2tpf19.hongyihualang.cn
可以看到 目前已经是最新的版本了。
2r7797.kvb1987.com
Git算不算程序员的必备技能？
3yyth8.kvb1981.com
2qb35l.compasslandconsultants.com
3xza10.hothairybushes.com
git reset --hard 6fcfc89来恢复了。演示如下：
2xrqu0.kvb1983.com
通过上面的显示我们可以知道，增加内容3333的版本号是 6fcfc89.我们现在可以命令
2svsqx.cdroutlet.com
Git算不算程序员的必备技能？
388nsu.hoodamath2.com
4fpomw.kvb1981.com
2o0tbx.compasslandconsultants.com
43h6rl.kvb1992.com
3ybdl4.hongyihualang.cn
3v6mbn.compasslandconsultants.com
3hwxsv.kvb1993.com
3wznex.kvb1986.com
git reset --hard 版本号 ，但是现在的问题假如我已经关掉过一次命令行或者333内容的版本号我并不知道呢？要如何知道增加3333内容的版本号呢？可以通过如下命令即可获取到版本号：git reflog 演示如下：
3tu9vh.kvb1992.com
3ytxqg.kvb1991.com
3qrsiq.kvb1982.com
我们看到 增加333333 内容我们没有看到了，但是现在我想回退到最新的版本，如：有333333的内容要如何恢复呢？我们可以通过版本号回退，使用命令方法如下：
3ayym7.hothairybushes.com
Git算不算程序员的必备技能？
3baosz.hongyihualang.cn
可以看到，内容已经回退到上一个版本了。我们可以继续使用git log 来查看下历史记录信息，如下：
342xeb.kvb1978.com
3e5tji.hoodamath2.com
3fbje4.cdroutlet.com
Git算不算程序员的必备技能？
3m8xeg.kvb1989.com
2unqkx.ecvyksp.cn
再来查看下 readme.txt内容如下：通过命令cat readme.txt查看
3j9952.misturabela.com
3jdxcy.hongyihualang.cn
3fwpkx.ecvyksp.cn

---

# v5463lkj
Auto-created repository for publishing - 2026-09-15T06:37:47.282Z
