![image](https://github.com/user-attachments/assets/29e83f83-331e-4036-af04-3fcada7af173)



No. &nbsp; Command &nbsp; Description
1 &nbsp; git&nbsp;config&nbsp;--global&nbsp;user.name&nbsp;"[firstname&nbsp;lastname]" &nbsp; Set&nbsp;a&nbsp;name&nbsp;that&nbsp;is&nbsp;identifiable&nbsp;for&nbsp;credit&nbsp;when&nbsp;reviewing&nbsp;version&nbsp;history.
2 &nbsp; git&nbsp;config&nbsp;--global&nbsp;user.email&nbsp;"[valid-email]" &nbsp; Set&nbsp;an&nbsp;email&nbsp;address&nbsp;that&nbsp;will&nbsp;be&nbsp;associated&nbsp;with&nbsp;each&nbsp;history&nbsp;marker.
3 &nbsp; git&nbsp;config&nbsp;--global&nbsp;color.ui&nbsp;auto &nbsp; Set&nbsp;automatic&nbsp;command&nbsp;line&nbsp;coloring&nbsp;for&nbsp;Git&nbsp;for&nbsp;easy&nbsp;reviewing.
4 &nbsp; git&nbsp;init &nbsp; Initialize&nbsp;an&nbsp;existing&nbsp;directory&nbsp;as&nbsp;a&nbsp;Git&nbsp;repository.
5 &nbsp; git&nbsp;clone&nbsp;[url] &nbsp; Retrieve&nbsp;an&nbsp;entire&nbsp;repository&nbsp;from&nbsp;a&nbsp;hosted&nbsp;location&nbsp;via&nbsp;URL.
6 &nbsp; git&nbsp;status &nbsp; Show&nbsp;modified&nbsp;files&nbsp;in&nbsp;the&nbsp;working&nbsp;directory,&nbsp;staged&nbsp;for&nbsp;your&nbsp;next&nbsp;commit.
7 &nbsp; git&nbsp;add&nbsp;[file] &nbsp; Add&nbsp;a&nbsp;file&nbsp;as&nbsp;it&nbsp;looks&nbsp;now&nbsp;to&nbsp;your&nbsp;next&nbsp;commit&nbsp;(stage).
8 &nbsp; git&nbsp;reset&nbsp;[file] &nbsp; Unstage&nbsp;a&nbsp;file&nbsp;while&nbsp;retaining&nbsp;the&nbsp;changes&nbsp;in&nbsp;the&nbsp;working&nbsp;directory.
9 &nbsp; git&nbsp;diff &nbsp; Diff&nbsp;of&nbsp;what&nbsp;is&nbsp;changed&nbsp;but&nbsp;not&nbsp;staged.
10 &nbsp; git&nbsp;diff&nbsp;--staged &nbsp; Diff&nbsp;of&nbsp;what&nbsp;is&nbsp;staged&nbsp;but&nbsp;not&nbsp;yet&nbsp;committed.
11 &nbsp; git&nbsp;commit&nbsp;-m&nbsp;"[descriptive&nbsp;message]" &nbsp; Commit&nbsp;your&nbsp;staged&nbsp;content&nbsp;as&nbsp;a&nbsp;new&nbsp;commit&nbsp;snapshot.
12 &nbsp; git&nbsp;branch &nbsp; List&nbsp;your&nbsp;branches.&nbsp;A&nbsp;*&nbsp;will&nbsp;appear&nbsp;next&nbsp;to&nbsp;the&nbsp;currently&nbsp;active&nbsp;branch.
13 &nbsp; git&nbsp;branch&nbsp;[branch-name] &nbsp; Create&nbsp;a&nbsp;new&nbsp;branch&nbsp;at&nbsp;the&nbsp;current&nbsp;commit.
14 &nbsp; git&nbsp;checkout &nbsp; Switch&nbsp;to&nbsp;another&nbsp;branch&nbsp;and&nbsp;check&nbsp;it&nbsp;out&nbsp;into&nbsp;your&nbsp;working&nbsp;directory.
15 &nbsp; git&nbsp;merge&nbsp;[branch] &nbsp; Merge&nbsp;the&nbsp;specified&nbsp;branch’s&nbsp;history&nbsp;into&nbsp;the&nbsp;current&nbsp;one.
16 &nbsp; git&nbsp;log &nbsp; Show&nbsp;all&nbsp;commits&nbsp;in&nbsp;the&nbsp;current&nbsp;branch’s&nbsp;history.
17 &nbsp; git&nbsp;log&nbsp;branchB..branchA &nbsp; Show&nbsp;the&nbsp;commits&nbsp;on&nbsp;branchA&nbsp;that&nbsp;are&nbsp;not&nbsp;on&nbsp;branchB.
18 &nbsp; git&nbsp;log&nbsp;--follow&nbsp;[file] &nbsp; Show&nbsp;the&nbsp;commits&nbsp;that&nbsp;changed&nbsp;file,&nbsp;even&nbsp;across&nbsp;renames.
19 &nbsp; git&nbsp;diff&nbsp;branchB...branchA &nbsp; Show&nbsp;the&nbsp;diff&nbsp;of&nbsp;what&nbsp;is&nbsp;in&nbsp;branchA&nbsp;that&nbsp;is&nbsp;not&nbsp;in&nbsp;branchB.
20 &nbsp; git&nbsp;show&nbsp;[SHA] &nbsp; Show&nbsp;any&nbsp;object&nbsp;in&nbsp;Git&nbsp;in&nbsp;human-readable&nbsp;format.
21 &nbsp; git&nbsp;rm&nbsp;[file] &nbsp; Delete&nbsp;the&nbsp;file&nbsp;from&nbsp;the&nbsp;project&nbsp;and&nbsp;stage&nbsp;the&nbsp;removal&nbsp;for&nbsp;commit.
22 &nbsp; git&nbsp;mv&nbsp;[existing-path]&nbsp;[new-path] &nbsp; Change&nbsp;an&nbsp;existing&nbsp;file&nbsp;path&nbsp;and&nbsp;stage&nbsp;the&nbsp;move.
23 &nbsp; git&nbsp;log&nbsp;--stat&nbsp;-M &nbsp; Show&nbsp;all&nbsp;commit&nbsp;logs&nbsp;with&nbsp;an&nbsp;indication&nbsp;of&nbsp;any&nbsp;paths&nbsp;that&nbsp;moved.
24 &nbsp; git&nbsp;stash &nbsp; Save&nbsp;modified&nbsp;and&nbsp;staged&nbsp;changes.
25 &nbsp; git&nbsp;stash&nbsp;list &nbsp; List&nbsp;stack-order&nbsp;of&nbsp;stashed&nbsp;file&nbsp;changes.
26 &nbsp; git&nbsp;stash&nbsp;pop &nbsp; Write&nbsp;working&nbsp;from&nbsp;top&nbsp;of&nbsp;stash&nbsp;stack.
27 &nbsp; git&nbsp;stash&nbsp;drop &nbsp; Discard&nbsp;the&nbsp;changes&nbsp;from&nbsp;top&nbsp;of&nbsp;stash&nbsp;stack.
28 &nbsp; git&nbsp;remote&nbsp;add&nbsp;[alias]&nbsp;[url] &nbsp; Add&nbsp;a&nbsp;git&nbsp;URL&nbsp;as&nbsp;an&nbsp;alias.
29 &nbsp; git&nbsp;fetch&nbsp;[alias] &nbsp; Fetch&nbsp;down&nbsp;all&nbsp;the&nbsp;branches&nbsp;from&nbsp;that&nbsp;Git&nbsp;remote.
30 &nbsp; git&nbsp;merge&nbsp;[alias]/[branch] &nbsp; Merge&nbsp;a&nbsp;remote&nbsp;branch&nbsp;into&nbsp;your&nbsp;current&nbsp;branch&nbsp;to&nbsp;bring&nbsp;it&nbsp;up&nbsp;to&nbsp;date.
31 &nbsp; git&nbsp;push&nbsp;[alias]&nbsp;[branch] &nbsp; Transmit&nbsp;local&nbsp;branch&nbsp;commits&nbsp;to&nbsp;the&nbsp;remote&nbsp;repository&nbsp;branch.
32 &nbsp; git&nbsp;pull &nbsp; Fetch&nbsp;and&nbsp;merge&nbsp;any&nbsp;commits&nbsp;from&nbsp;the&nbsp;tracking&nbsp;remote&nbsp;branch.
33 &nbsp; git&nbsp;rebase&nbsp;[branch] &nbsp; Apply&nbsp;any&nbsp;commits&nbsp;of&nbsp;the&nbsp;current&nbsp;branch&nbsp;ahead&nbsp;of&nbsp;the&nbsp;specified&nbsp;one.
34 &nbsp; git&nbsp;reset&nbsp;--hard&nbsp;[commit] &nbsp; Clear&nbsp;staging&nbsp;area,&nbsp;rewrite&nbsp;working&nbsp;tree&nbsp;from&nbsp;specific&nbsp;commit.
35 &nbsp; git&nbsp;config&nbsp;--global&nbsp;core.excludesfile&nbsp;[file] &nbsp; System-wide&nbsp;ignore&nbsp;pattern&nbsp;for&nbsp;all&nbsp;local&nbsp;repositories.
