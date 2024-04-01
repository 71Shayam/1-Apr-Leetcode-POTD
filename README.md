 int lengthOfLastWord(string s) {
         int sizee=s.size(),count=0,flag=0;
        for(int i=sizee-1;i>=0;i--){
            if(s[i]==' '&&flag)break;
            if(s[i]!=' '){
                flag=1;
                count++;
            }
        }
        return count;
    }
