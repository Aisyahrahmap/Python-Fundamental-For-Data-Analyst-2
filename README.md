# Pandas Library
Pandas is well-suited for working with tabular data, such as spreadsheets or SQL tables.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/42a0604f-0173-4dd4-bec7-0a954f50a3bd" /></div>

# Data Structures in Pandas Library
Pandas generally provide two data structures for manipulating data. They are:
* Series
* DataFrame
## 1. Pandas Series
A Pandas Series is a one-dimensional labeled array capable of holding data of any type (integer, string, float, Python objects, etc.). The axis labels are collectively called indexes.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/241f5066-6e3b-4ea3-b637-2d9d0f4e7e76" /></div>
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/5b699c6d-225a-4ab5-b069-6e5c4c8f836d" /></div>
Pandas Series index attribute is used to get or set the index labels of the given Series object.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/8627ece0-fb23-4504-9559-67112e3a73a6" /></div>
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/cb95450a-833b-4161-9950-c95bb87de0db" /></div>

### Create a Series with a random explicit string index.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/32c51435-74d9-460b-89cd-3ba87626ba55" /></div>

Pandas Series index attribute is used to get or set the index labels of the given Series object.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/6ed94be6-cafb-4039-907f-23c67cc36955" /></div>

Indexing makes use of explicit index.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/352efef0-3f59-470d-9557-383c075d48ca" /></div>

On the other hand, in Pandas, the term 'implicit index' refers to the default index that Pandas assigns to each element in a Series or DataFrame when no explicit index is provided.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/6bd96bfa-e19e-47d6-823f-4a60d3d6d424" /></div>

## loc and iloc
let's creating a sample dataset with matching implicit and explicit indices.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/79af5350-6290-44b2-886c-a3bc08c6faa6" /></div>
To clarify data retrieval, we can use the loc and iloc attributes.

### loc
The loc attribute allows indexing and slicing that always references the explicit index.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/70e4fc9c-8bea-4ebe-9668-17b9231a841c" /></div>

### iloc
The iloc attribute allows indexing and slicing that always refer to the implicit integer index.
<div align="center"><img src="https://github.com/Aisyahrahmap/Python-Fundamental-For-Data-Analyst-2/assets/166115307/21035509-cd4c-4ae2-8c4f-2a1e4b643e70" /></div>









