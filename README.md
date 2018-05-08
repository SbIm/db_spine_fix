# db_spine_fix
drangonbones(5.6) to spine format fixer

当没有产生动画时，db 5.6版本导出到spine格式时会忽略掉对0帧key,   
以及导出的文件缺少了spine版本信息
这个python脚本会对它进行修复
