> This site was built using [GitHub Pages](https://pages.github.com/).

# PROGRAM TO CALCULATE DOT PRODUCT
## MATHEMATICAL EXPRESSIONS
### Dot product formula:
**This is bold text**
**$$\left( A \cdot B = \sum_{i=1}^{n} A_i \cdot B_i \right)$$**
### List Example:
- apple
* banana
+ mango

### Task List:
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:


### Code Example:
```C++
vector<int> dotprod(vector<int> a,vector<int> b){
    vector<int> ans;
    for(int i = 0;i<a.size();i++){
        ans.push_back(a[i]*b[i]);
    }
    return ans;
}
int main(){
    vector<int> a = {1,2,3};
    vector<int> b = {2,3,4};
    vector<int> ans = dotprod(a,b);
    for(int i = 0;i<ans.size();i++){
        cout<<ans[i]<<" ";
    }
}
```
## Example image
![here is a image of projection of a vector](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3e/Dot_Product.svg/300px-Dot_Product.svg.png)

## DIFFERENT VERSION
| vector | equivalent |
| ----------- | ----------- |
| a.b | b.a |
| a.b | abcos | 

### Footnote Example:
Here is a simple footnote[^1].
A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.
  


### Alerts:
> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!TIP]
> Helpful advice for doing things better or more easily.


