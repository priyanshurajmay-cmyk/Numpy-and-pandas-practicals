# Numpy-and-pandas-practicals

## Series
### Create Series
```
# Create series from Nump Array
v = np.array([1,2,3,4,5,6,7])
s1 = pd.Series(v)
print(s1)
```
output:

<img width="113" height="137" alt="image" src="https://github.com/user-attachments/assets/83a6b2c2-0961-400f-8b85-753be5fb9cad" />

```
#Datatype of Series
s1.dtype
```
<img width="102" height="55" alt="image" src="https://github.com/user-attachments/assets/8e132dd4-e9df-4b28-97b9-55db140687fd" />

The code will give error , since it should be ```s.size```
```
# number of bytes allocated to each item
s1.itemsize
```
