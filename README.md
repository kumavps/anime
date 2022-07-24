# MOD NONTON ANIME

## Lucky
- resign with test signature
- signature verification killer

## APK Lab
- no-res
- no-assets

## DNS
### java
```
void u
```
### smali
```
.method private u()V
    .locals 2
    
    return-void
.end method
```


## ADS
### java
```
void j0
```
### smali
```
.method private j0(Z)V
    .locals 8

    .line 1
    iget-object v0, p0, Lcom/stream/neoanimex/activities/MainActivity;->f:Lcom/android/billingclient/api/a;

    invoke-virtual {v0}, Lcom/android/billingclient/api/a;->b()Z

    move-result v0

    if-eqz v0, :cond_0

    const/4 v2, 0x0

    const-string v3, "remove_ads"

    const/4 v4, 0x1

    .line 2
    iget-object p1, p0, Lcom/stream/neoanimex/activities/MainActivity;->e:Landroid/content/SharedPreferences;

    invoke-interface {p1}, Landroid/content/SharedPreferences;->edit()Landroid/content/SharedPreferences$Editor;

    move-result-object p1

    invoke-interface {p1, v3, v4}, Landroid/content/SharedPreferences$Editor;->putBoolean(Ljava/lang/String;Z)Landroid/content/SharedPreferences$Editor;

    move-result-object p1

    invoke-interface {p1}, Landroid/content/SharedPreferences$Editor;->apply()V

    .line 3
    iget-object p1, p0, Lcom/stream/neoanimex/activities/MainActivity;->e:Landroid/content/SharedPreferences;

    invoke-interface {p1, v3, v2}, Landroid/content/SharedPreferences;->getBoolean(Ljava/lang/String;Z)Z

    move-result p1

    iput-boolean p1, p0, Lcom/stream/neoanimex/activities/MainActivity;->i:Z

    .line 4
    invoke-direct {p0}, Lcom/stream/neoanimex/activities/MainActivity;->O()V

    const-string v1, "Mod by JemJem"

    .line 5
    invoke-static {p0, v1, v2}, Landroid/widget/Toast;->makeText(Landroid/content/Context;Ljava/lang/CharSequence;I)Landroid/widget/Toast;

    move-result-object v1

    invoke-virtual {v1}, Landroid/widget/Toast;->show()V

    :cond_0
    return-void
.end method
```
