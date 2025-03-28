# WHUCS_MentorGuide
这是一款武汉大学计算机学院导师管理系统
用户可以查看导师评价并筛选自己心仪的导师
欢迎使用
else if(cause == 13 || cause == 15) {
uint64 fault_va = r_stval();  // 获取出错的虚拟地址
if(fault_va >= p->sz
// 如果第二个条件不满足,说明当前发生的是COW写入错误
|| cowpage(p->pagetable, fault_va) != 0
// 当前发生COW写入错误时,继续进入到第三个判断
// 该判断负责处理COW写入错误,即分配一个新页面
|| cowalloc(p->pagetable, PGROUNDDOWN(fault_va)) == 0)
p->killed = 1;
}
1111111111111111111111