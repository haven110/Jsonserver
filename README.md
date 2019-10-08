//获取所有用户信息
http：//localhost:3000/users

//获取id为1的用户信息
http：//localhost:3000/users/1

//获取公司的所有信息
http：//localhost:3000/companies

//获取单个公司的信息
http：//localhost:3000/companies/1

//获取所有公司id为3的用户
http：//localhost:3000/companier/3/users


//获取公司名字获取信息
http：//localhost:3000/companies?name=soft

//获取公司多个名字获取信息
http：//localhost:3000/companies?name=soft&name=Apple

//获取一页中只有俩条数据
http：//localhost:3000/companies?_page=1&_limit=2


//升序排序  asc升序 desc降序

http：//localhost:3000/companies?_sort=name&_order=asc

先创建一个jsonserve文件，在cmd窗口-> npm install json-server --save  ->npm init   ->npm install -g json-server 




