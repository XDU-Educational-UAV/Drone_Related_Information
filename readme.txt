
΢���������������:

         HEAD
	M4  ��  M1
	   \     /
	    \   /
	     \ /
	     / \
	    /   \
	   /     \
	M3     M2
	
Ӳ����Դ:
	1,MCU:STM32G030K8T6 (FLASH:512K, RAM:128K, ϵͳ����ʱ��Ƶ��:96MHz)
	2,6��MPU6050������IIC1��(IMU_SCL:PB8, IMU_SDA:PB7, ͨ�ŷ�ʽ:ģ��IIC) 
	3,��������ͨ��NFR51822������UART1��(RXD:PA3, TXD:PA2, NRF_FLOW_CTRL:PA4) 
	4,MOTOR1������TIM4_CH2��(PB6)
	5,MOTOR2������TIM4_CH1��(PB3)
	6,MOTOR3������TIM2_CH3��(PA9/PA11)
	7,MOTOR4������TIM2_CH1��(PB8)
	8,MOTOR1��Ӧ����ɫLED��������PB5�ϣ��ߵ�ƽ��Ч
	9,MOTOR2��Ӧ����ɫLED��������PB4�ϣ��ߵ�ƽ��Ч
	10,MOTOR3��Ӧ����ɫLED��������PC8�ϣ��ߵ�ƽ��Ч
	11,MOTOR4��Ӧ����ɫLED��������PB9�ϣ��ߵ�ƽ��Ч
