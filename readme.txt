
微型四轴飞行器外形:

         HEAD
	M4  ↑  M1
	   \     /
	    \   /
	     \ /
	     / \
	    /   \
	   /     \
	M3     M2
	
硬件资源:
	1,MCU:STM32G030K8T6 (FLASH:512K, RAM:128K, 系统运行时钟频率:96MHz)
	2,6轴MPU6050连接在IIC1上(IMU_SCL:PB8, IMU_SDA:PB7, 通信方式:模拟IIC) 
	3,蓝牙无线通信NFR51822连接在UART1上(RXD:PA3, TXD:PA2, NRF_FLOW_CTRL:PA4) 
	4,MOTOR1连接在TIM4_CH2上(PB6)
	5,MOTOR2连接在TIM4_CH1上(PB3)
	6,MOTOR3连接在TIM2_CH3上(PA9/PA11)
	7,MOTOR4连接在TIM2_CH1上(PB8)
	8,MOTOR1对应的绿色LED，连接在PB5上，高电平有效
	9,MOTOR2对应的绿色LED，连接在PB4上，高电平有效
	10,MOTOR3对应的绿色LED，连接在PC8上，高电平有效
	11,MOTOR4对应的绿色LED，连接在PB9上，高电平有效
