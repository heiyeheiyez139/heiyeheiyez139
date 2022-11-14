- 👋 Hi, I’m @heiyeheiyez139
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
heiyeheiyez139/heiyeheiyez139 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
LEFT 0x4b00

#define RIGHT 0x4d00

#define DOWN 0x5000

#define UP 0x4800

#define Esc 0x011b

int i,j,key,k;

struct Food/*构造食物结构体*/

{

int x;

int y;

int yes;

}food;

struct Goods/*构造宝贝结构体*/

{

int x;

int y;

int yes;

}goods;

struct Block/*构造障碍物结构体*/

{

int x[m];

int y[m];

int yes;

}block;

struct Snake{/*构造蛇结构体*/

int x[N];

int y[N];

int node;

int direction;

int life;

}snake;

struct Game/*构建游戏级别参数体*/

{

int score;

int level;

int speed;

}game;

/*定义函数*/

void init(void);/*定义图形驱动*/

void close(void);/*定义关闭函数*/

void drawk(void);/*定义界面函数*/

void gameover(void);/*定义游戏结束函数*/

void gameplay(void);/*定义游戏主函数*/

void prscore(void);/*定义得分函数*/

void main(void){/*主函数体，调用以下四个函数*/

init();

setbkcolor(7);

drawk();

gameplay();

close();

}--->
