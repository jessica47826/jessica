import psutil

# 获取CPU的使用率
cpu_usage =util.cpu_percent()

# 获取CPU的核心数
cpu_cores = psutil.cpu_count(logical=False)

# 打印CPU的使用率和核心数
print(" usage: {}%".format(cpu_usage))
print("CPU cores: {}".format(cpu_cores))
