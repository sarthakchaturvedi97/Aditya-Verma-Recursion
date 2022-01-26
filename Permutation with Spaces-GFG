class Solution
{
public:
    void getSorted(string op,string S,vector<string> &result)
    {
        if(S.length()==0)
        {
            result.push_back(op);
            return;
        }
        string op1=op;
        string op2=op;
        op1.push_back(' ');
        op1.push_back(S[0]);
        op2.push_back(S[0]);
        S.erase(S.begin());
        getSorted(op1,S,result);
        getSorted(op2,S,result);
        return;
    }
    vector<string> permutation(string S){
        // Code Here
        vector<string> result;
        string op;
        op.push_back(S[0]);
        S.erase(S.begin());
        getSorted(op,S,result);
        return result;
    }
};
