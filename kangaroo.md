# HACKERS_RANK-
char* kangaroo(int x1, int v1, int x2, int v2) {

if(v1>v2)
{
    if((x2-x1)%(v1-v2) == 0)
        return("YES");
    else
        return("NO");
}
else
    return("NO");
}

int main()
{
    
    int x1;
    int v1;
    int x2;
    int v2;
    scanf("%i %i %i %i", &x1, &v1, &x2, &v2);
    int result_size;
    char* result = kangaroo(x1, v1, x2, v2);
    printf("%s\n", result);
    return 0;
}
