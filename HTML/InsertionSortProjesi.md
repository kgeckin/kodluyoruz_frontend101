# KodluyoruzInsertionSortProjesi


## Soru1
### <table><tr><td>[22,27,16,2,18,6] yanda verilen dizinin sort türüne göre aşamalarını yazınız.</td></tr></table>


| 22  | 27  | 16  | 2   | 18  | 6   |
| :-: | :-: | :-: | :-: | :-: | :-: |
| <strong><em>2</strong></em>  | 27  | 16  | <strong><em>22</strong></em>   | 18  | 6   |
| 2  | <strong><em>6</strong></em>  | 16  | 22   | 18  | <strong><em>27</strong></em>   |
| 2  | 6  | 16  | <strong><em>18</strong></em>   | <strong><em>22</strong></em>  | 27   |

### <table><tr><td> Big-O gösterimini yazınız.</td></tr></table>
```
O(n^2)
```
### <table><tr><td> Time Complexity: Average case, Worst case,  Best case. </td></tr></table>

>Average case: Aradığımız sayının ortada olmasıdır =>O(n^2)
> 
>Worst case: Aradığımız sayının sonda olmasıdır =>O(n^2) 
>
>Best case: Aradığımız sayının dizinin en başında olmasıdır =>O(n)

### <table><tr><td> Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? </td></tr></table>
```
Average case
```
## Soru2
### <table><tr><td>[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız</td></tr></table>


| 7  | 3  | 5  | 8   | 2  | 9   | 4   | 15  | 6   |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| <strong><em>2</strong></em>  |  3 | 5  |  8  |  <strong><em>7</strong></em> |  9  |  4 | 15  |  6  |
|2|3|<strong><em>4</strong></em>|8|7|9|<strong><em>5</strong></em>|15|6|
|2|3|4|<strong><em>5</strong></em>|7|9|<strong><em>8</strong></em>|15|6|
|2|3|4|5|<strong><em>6</strong></em>|9|8|15|<strong><em>7</strong></em>|

