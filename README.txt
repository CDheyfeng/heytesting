**接口自动化框架核心部件**
____
1. 测试数据与业务分离
2. 接口上下文依赖
3. 参数化
4. 用例自动生成& pairwise结对测试用例组织（正交分析）
5. pytest fixtures
____
存放测试数据、放在conftest.py、作用范围：session>module>class>function
fixtures参数化:params可以是list、tuple、字典列表、字典元祖
pytest的内置fixtures
____
1. pytest.ini,主要的配置文件
2. conftest.py 本地插件库，主要包括hook，fixture
3. pytest-check 复合断言

	
