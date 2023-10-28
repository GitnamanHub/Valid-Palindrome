class Solution {
public:
    bool isPalindrome(string s) {
        int n=s.length();
        string word = {};
        for(int i=0;i<n;i++)
        {
            char a = s[i];
            
            if(a >= 'A' && a<= 'Z')
            a+=32;
            if((a >='a'&& a<='z') || (a>='0' && a<='9'))
            {
                word += a;
            }
        }

        int l=word.length();

        if(l==0)
        return true;
        else
        {
            for(int i=0;i<=l/2;i++)
            {
                if(word[i]!=word[l-i-1])
                return false;
            }
        }
        return true;
    }
};
