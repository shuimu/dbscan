# dbscan

===== challenge 1: git的使用 =====

1. 从github到本地:

git pull: 从git中拉取到本地

2. 从本地到github

git add *

git commit -m "update"

git push


===== challenge 1: 使用octave生成测试集 ======

1. octave code

------ first circle -----

生成100个theta值

theta1 = rand(100,1) * 2 * pi

x1 = sin(theta1) * 1

y1 = cos(theta1) * 1

plot(x1, y1, 'r * ')


----- second circle -----

theta2 = rand(100,1) * 2 * pi

x2 = sin(theta2) * 2

y2 = cos(theta2) * 2

plot(x2, y2, 'r * ')

plot(x1, y1, 'r * ', x2, y2, 'b * ')


