# JC-JMeter-Task

 ![Logo](https://storage.googleapis.com/danacita-website-v3-prd/website_v3/images/JuaraCoding-LogoPartnerPageBanner2.original.png)

## Material

* Performance Testing
    * Test case target `api.themoviedb.org`

* Test Case Parameter
  * Global Variable
    * `base_url : api.themoviedb.org`
    * `my_token : Bearer token`
  
  * Thread Group
    * `User : 100` 
    * `Delay : 50` 
    * `Loop : 10`
  
  * Path Target
    * `/3/movie/top_rated`
    * `/3/movie/upcoming`
    * `/3/movie/{movie_id}/rating`
  * Http request
    * Get
      * `top_rated`
      * `upcoming`
    * Post
      * `rating`

## Test Result
   * ### Test Process
   [![TestVideo](https://img.youtube.com/vi/YeVWcX4yJ7g/0.jpg)](https://www.youtube.com/watch?v=YeVWcX4yJ7g)

   * ### Report Test
   <img alt="Logo" height="" src="https://lh3.googleusercontent.com/fife/AK0iWDweH2KAgY2WkraB3WjBdPahFyLI2xyRb53_z0qDQGRvFPthF7HbLsgG1fzvnMybfvW3cdUqBTSzOsd4hSg-XwrViZZTJ6TZMR_fkl3kik-S_Zg5U-VopKG-fAsXaLffWNy9Ib2RQc4tndI75_4V0tMkiKp9CXiZKJEEvggp2Tn3N0E2Ryu6K--O3F8XN_pPVg0an-XwrVmeHbQLnvg2jH6SaGkrgq-Ya9Hrv6KoGB3DyxhtykLgo91xEFu_sCutN-bb9vv7zigdLSDl8qjs4a2TrVYowfjVYrdnrLA4sYawzHnRZTyd_QuabAh8cKYnTMNniC9dLcF0duMMGYX6vTe3hwoZK7BUl9H8q2f_h142F4q81j24o7Hsu7UqUju3nI6Pd2l9l2gErwetRe76ShrfTbe9qFJuqMsw6U4mvRwoEf7KP2Wz05OSnZaxZtJo8U161NgbDyDfLgVaUi815DEZ5SVX7XSqqXfXlKFhV7y0ZrPZTN664jYRTDGMOhDQP2MQ3bFblkV29sEi4E6_BkT8kT-dje8mf9n-GTLx34HNXErW83qjKUONZhQb0aOo_yHXPKT9LzJ5kz6-T8Suhex6z30qzch3VFX7lIrgkxcmyd7MEVe40iPY3wmVADWMsULD-_bPuUP41F0ycSN3BOTH0Bcls1_FR0ztoKJ6XCpYhIC4na2OWKHlVA8wch6GTt_kUeL4q7Qr3B4TYO2s0BKIPIwJKOF6px7mu_2Up1gles89ofTDeG4vZf13RjHqimK2dt2PH_xCTXZHrBfXSiAYTRMyr0-RkrRE8xWh5lY19U1p-xQvR-jGRvht9gP9Xpoe6yC-CpuBF3t8M6sCn0BySCOaOgrZSnmVLNNmti-K1EAeK-xxbxAsjIJ6fC8rTwC2EVSY6h0FYW4-hKNJnYP6RnVQt2ZtUS-EkFx5wsDxp6VsS1PVQatNmVIKhipCSejPcy4GxPTLQ_BFkA1gte-HxWzamkqDL8Sx_0zPAfD1KncdmZIl2P8usX-hfKwpVsGLVe9ZNqZ3ityKKWoal272jRX79PpaJEI3TFNQlmA8PdgJdQGjLrleYyeF-5c_HH2Ca3ZrVxFJXFd3L8jmm_e0htGn0XocO-Ow2f4PM8YsRtydGpa86-HBEmiQKJAyr-w2vEz1zx_MTRBjviXs1y-2lEUACIr6lCCt9ckMj6ndrDerVz-aueebrz2N8ckAJNy4I1SrCbfPaPtabOI1pcPf7nKpOYz3f02hZRx9TRgepr0Lq8v01JvaGr3MW-cpx1ADN7MdFTrA5dRFdkfHHLXfrSe5MrEk22djBcSL43WihzOUwJFzwSbz3n53bBIKaXHK70VtAfZ36a6rZsOQh_Vn-l8tDxFNODap8XSlFRtnfldWb1jSD0MnNazyU_FTUKMbzkHObvbwiuIKRo5z2y6QM2tlMiakTZjMLbVNTyhoFyd_bOMrcd4WKmmd8WmKlPAf7kFWQsbfjZIQgzQzAAzaYsJHNss7fgeRxOckxRv4zmUhk_f100Q7DKHH-hX_VLwxnec-BW42ag=w1440-h785" width=""/>

## Authors

[Aldi Triavin](https://github.com/triavin)
