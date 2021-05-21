//获取所有用户信息
http://localhost:3000/users
//获取单个用户
http://localhost:3000/users/1

//获取所有公司所有信息
http://localhost:3000/companies

//获取单个公司
http://localhost:3000/companies/1

//获取公司为3的用户
http://localhost:3000/companies/3/users

//根据多个名字获取公司信息
http://localhost:3000/companies?name=Apple&name=Microsoft

//获取一页中只有两个数据
http://localhost:3000/companies?_pageg=1&_limit=2

//升序排序
http://localhost:3000/companies?_sort=name&_order=asc


//获取年龄为30以上
http://localhost:3000/users?age_gte=30

//获取年龄为30~40
http://localhost:3000/users?age_gte=30&age_lte=40

//搜索用户信息
http://localhost:3000/users?q=k