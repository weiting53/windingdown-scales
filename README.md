# WindingDown 補填問卷

WindingDown 研究受試者補填自我控制（BSCS）、手機使用（SPAI-SF）、人際與資訊（FoMO）量表的網頁版。題目與 App 內版本相同。

回應寫入 Supabase `drift_scale_web` 表（只能新增、不能讀取）。一般連結請受試者填名字，研究人員事後對應成編號並刪除名字；專屬連結 `?p=編號` 直接帶入編號。
