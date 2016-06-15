struct date               /* 定义日期结构类型 */
{
	int year;
	int month;
	int day;
}

struct marriedState       /* 定义已婚结构类型 */
{
	struct date marryDate;
	char spouseName[20];
	int childCount;
}

struct divorceState       /* 定义离婚结构类型 */
{
	struct date divorceDate[];
	int childCount;
}

union maritalState        /* 定义婚姻状况联合类型 */
{
	int singel;
	struct marriedState married;
	struct divorceState divorce;
}

struct person             /* 定义职工个人信息结构类型 */ 
{
	char name[20];
	char sex;
	int age;
	union maritalState;
	int marryFlag;
}