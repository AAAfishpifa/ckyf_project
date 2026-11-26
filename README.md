# ckyf_project
for ckyf

task_01是“外接LED灯以500ms周期进行闪烁，使用了HAL_Delay”

task_02是“外接LED灯以500ms周期进行闪烁，不使用HAL_Delay，而是使用了计时器TIM2”

task_03是“按键通过EXIT中断控制LED灯开关，包含有20ms的软件消抖”

task_0201是第二次作业第1题

task_0202是第二次作业第2题，其中TIM3的PSC=71，ARR=999；TIM4的PSC=71,ARR=9999;CCR与角度(angle)的换算公式如下：CCR=500+（angle*2000/180）

task_0203是第二次作业第3题（已经将第5题合并进去）（换算公式：U(电压)=(ADC*3.3)/4095，angle=(ADC*180)/4095，CCR=500+(angle*2000)/180=500+(ADC*2000)/4095）

task_0204是第二次作业第4题（从task0201和0202里面拿东西拼的）

致敬传奇铁头山羊的教程和老登的交流喵喵喵