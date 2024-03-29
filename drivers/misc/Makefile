
# Makefile for misc devices that really don't fit anywhere else.
#

obj-$(CONFIG_IBM_ASM)		+= ibmasm/
obj-$(CONFIG_AD525X_DPOT)	+= ad525x_dpot.o
obj-$(CONFIG_AD525X_DPOT_I2C)	+= ad525x_dpot-i2c.o
obj-$(CONFIG_AD525X_DPOT_SPI)	+= ad525x_dpot-spi.o
0bj-$(CONFIG_INTEL_MID_PTI)	+= pti.o
obj-$(CONFIG_ATMEL_PWM)		+= atmel_pwm.o
obj-$(CONFIG_ATMEL_SSC)		+= atmel-ssc.o
obj-$(CONFIG_ATMEL_TCLIB)	+= atmel_tclib.o
obj-$(CONFIG_BMP085)		+= bmp085.o
obj-$(CONFIG_ICS932S401)	+= ics932s401.o
obj-$(CONFIG_LKDTM)		+= lkdtm.o
obj-$(CONFIG_TIFM_CORE)		+= tifm_core.o
obj-$(CONFIG_TIFM_7XX1)		+= tifm_7xx1.o
obj-$(CONFIG_PHANTOM)		+= phantom.o
obj-$(CONFIG_SENSORS_BH1780)	+= bh1780gli.o
obj-$(CONFIG_SENSORS_BH1770)	+= bh1770glc.o
obj-$(CONFIG_SENSORS_APDS990X)	+= apds990x.o
obj-$(CONFIG_ANDROID_PMEM)	+= pmem.o
obj-$(CONFIG_SGI_IOC4)		+= ioc4.o
obj-$(CONFIG_ENCLOSURE_SERVICES) += enclosure.o
obj-$(CONFIG_KGDB_TESTS)	+= kgdbts.o
obj-$(CONFIG_SGI_XP)		+= sgi-xp/
obj-$(CONFIG_SGI_GRU)		+= sgi-gru/
obj-$(CONFIG_CS5535_MFGPT)	+= cs5535-mfgpt.o
obj-$(CONFIG_HP_ILO)		+= hpilo.o
obj-$(CONFIG_APDS9802ALS)	+= apds9802als.o
obj-$(CONFIG_ISL29003)		+= isl29003.o
obj-$(CONFIG_ISL29020)		+= isl29020.o
obj-$(CONFIG_SENSORS_TSL2550)	+= tsl2550.o
obj-$(CONFIG_EP93XX_PWM)	+= ep93xx_pwm.o
obj-$(CONFIG_DS1682)		+= ds1682.o
obj-$(CONFIG_TI_DAC7512)	+= ti_dac7512.o
obj-$(CONFIG_UID_STAT)		+= uid_stat.o
obj-$(CONFIG_C2PORT)		+= c2port/
obj-$(CONFIG_IWMC3200TOP)      += iwmc3200top/
obj-$(CONFIG_HMC6352)		+= hmc6352.o
obj-y				+= eeprom/
obj-y				+= cb710/
obj-$(CONFIG_MPU_SENSORS_MPU3050) += mpu3050/
obj-$(CONFIG_MPU_SENSORS_MPU6050) += inv_mpu/
obj-$(CONFIG_SPEAR13XX_PCIE_GADGET)	+= spear13xx_pcie_gadget.o
obj-$(CONFIG_VMWARE_BALLOON)	+= vmw_balloon.o
obj-$(CONFIG_ARM_CHARLCD)	+= arm-charlcd.o
obj-$(CONFIG_PCH_PHUB)		+= pch_phub.o
obj-y				+= ti-st/
obj-$(CONFIG_AB8500_PWM)	+= ab8500-pwm.o
obj-y				+= lis3lv02d/
obj-y				+= carma/
obj-$(CONFIG_WL127X_RFKILL)	+= wl127x-rfkill.o
obj-$(CONFIG_APANIC)		+= apanic.o
obj-$(CONFIG_SENSORS_AK8975)	+= akm8975.o
obj-$(CONFIG_SENSORS_AK8963)	+= akm8963.o
obj-$(CONFIG_SAMSUNG_C2C)	+= c2c/
obj-$(CONFIG_USBHUB_USB3503)	+= usb3503.o
obj-$(CONFIG_USBHUB_USB3503_OTG_CONN)	+= usb3503_otg_conn.o
obj-$(CONFIG_USBHUB_USB3803)	+= usb3803.o
ifeq ($(CONFIG_SEC_MODEM_P8LTE),y)
obj-$(CONFIG_SEC_MODEM)         += modem_if_na/
else ifeq ($(CONFIG_SEC_MODEM_U1_SPR),y)
obj-$(CONFIG_SEC_MODEM)		+= modem_if_na_spr/
else ifeq ($(CONFIG_SEC_MODEM_V2), y)
obj-$(CONFIG_SEC_MODEM)         += modem_v2/
else
obj-$(CONFIG_SEC_MODEM)		+= modem_if/
endif
obj-$(CONFIG_STMPE811_ADC)	+= stmpe811-adc.o
obj-$(CONFIG_JACK_MON)		+= jack.o
obj-$(CONFIG_UART_SELECT)	+= uart_select.o
obj-$(CONFIG_WIMAX_CMC)         += max8893.o
ifeq ($(CONFIG_MUIC_DET_JACK),y)
obj-$(CONFIG_SEC_DEV_JACK)	+= sec_jack_muic.o
else
obj-$(CONFIG_SEC_DEV_JACK)	+= sec_jack.o
endif
obj-$(CONFIG_PN544)		+= pn544.o
obj-$(CONFIG_FM34_WE395)	+= fm34_we395.o
obj-$(CONFIG_AUDIENCE_ES305)	+= es305.o
obj-y				+= 2mic/

obj-$(CONFIG_SLP_PROCESS_MON)	+= slp_process_monitor.o
obj-$(CONFIG_SLP_LOWMEM_NOTIFY)	+= slp_lowmem_notify.o

obj-$(CONFIG_MACH_M0_CTC)   += cw_tty.o

# Secure OS Mobicore Interface
obj-$(CONFIG_MOBICORE_SUPPORT)  += tzic.o
obj-$(CONFIG_MOBICORE_DRIVER)  += tzic.o

# Touchwake
obj-$(CONFIG_TOUCH_WAKE)	+= touch_wake.o

ifeq ($(TIMA_ENABLED),1)
obj-$(CONFIG_TIMA_LOG)		+= tima_debug_log.o
endif
