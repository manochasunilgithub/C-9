C# 9.0 at glance
C# continues it’s evolution journey and making programmers life easier. Though new features may not look very attractive but surely it will reduce the amount of code one needs to write to achieve target code, so less chances of making mistakes and of course code will look more readable and compact.
C# 9.0 needs .Net 5.0 framework. It’s good for C# developers to know these features whenever they start writing code.


Implicit Main ( No need to write file with main function)
Init properties
Record
Improved Pattern Matching
Native Ints


        if (str != String.Empty && str.Length > (from + maxlength))
            res = str.Substring(from, maxlength);
        else
            res = str;
        return res;
    }
}
