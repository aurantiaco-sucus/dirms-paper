* RmInit
    * 部署服务 rminit
* RmService/RmGuard
    * 启动基础服务 rmg-core
    * 启动yolod rmg-yolod
    * 启动RmAnalysis rmg-rma
* RmAdmin
    * 图片管理
        * 上传图片 rma-im-add
        * 查询图片 rma-im-as
    * 商品管理
        * 创建商品 rma-prod-add
        * 修改商品 rma-prod-mut
        * 删除商品 rma-prod-rm
        * 查询商品 rma-prod-as
        * AI商品描述生成 rma-ai-desc
        * AI商品价格生成 rma-ai-price
        * AI商品批量生成 rma-ai-bulk
    * 库存管理
        * 制定进货计划 rma-ir-plan
        * 执行进货计划 rma-ir-exec
        * 查看库存 rma-ir-as
        * 启动点货批次 rma-audit
    * 其他
        * 设置条码 rma-bc
        * 设置推荐商品 rma-feat
* RmAnalysis
    * 查看超市范例 demo-grocery
* ShopEyes Owner
    * 上传本地图片 seo-local
    * 上传拍照 seo-camera
    * 点货 seo-audit
* ShopEyes Guest
    * 搜索商品 seg-tx
    * 浏览推荐商品 seg-feat
    * 询问AI导购 seg-assist
* EasyDataset
    * 创建数据集 ed-nd
    * 创建类别 ed-nc
    * 单次拍照 ed-shot
    * 连拍 ed-burst
    * 删除照片 ed-rm
    * 标记照片为测试 ed-mark
* EasyCheckout
    * 条码结算 ec-bc
    * 称重调零 ec-tare
    * 称重结算 ec-wr