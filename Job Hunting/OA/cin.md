经常有傻逼公司要处理cin的东西

```c++
int main(){
    string line;
    while (getline(cin, line)){
        //这个时候line 就是这一行的string
        istringstream ss(line);
        string sub_str;
        while(getline(ss,str,'.')){ //最后一个参数seperator 
            //这时候str就是每个分割后的数字了
            vec.push_back(stoi(num));
        }
    }
}
```

#