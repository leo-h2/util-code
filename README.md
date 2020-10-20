
import numpy as np   

td_series = np.arange(10)   
diff_seires = (td_series[5:] - td_series[:-5])   

print(td_series)            # [0 1 2 3 4 5 6 7 8 9]   
print(td_series[5:])        # [5 6 7 8 9] 5번째 부터 읽기   
print(td_series[:-5])       # [0 1 2 3 4] 앞에서 5개 읽기   
print(diff_seires)          # [5 5 5 5 5]   
