# spring-boot-orm-learn_start_ubuntu
---
# Install git
![install_git][install_git]

# Git clone
```
//cd path
git clone https://github.com/hipark/spring-boot-orm-learn.git
```
![git_clone][git_clone]

# STS Download
[STS Download Link](https://spring.io/tools/sts/all)
![sts_download]

* 다운받은 spring-tool-suite-3.7.2.RELEASE-e4.5.1-win32-x86_64.zip 압축 풀고 원하는 장소에 위치 후 실행 + workspace 설정

# Install Gradle
1. Gradle Download  
[Gradle Download Page Link](http://gradle.org/gradle-download/)  
![install_gradle_1][install_gradle_1]

2. 압축 해제
![unpacking_gradle_zip_file][unpacking_gradle_zip_file]

3. 환경 변수 설정  
  Path에 GRADLE_HOME/bin 추가
```
//.profile 열기
sudo gedit ~/.profile
```
```
//맨 아래에 추가
export GRADLE_HOME=/home/jhpark/development/gradle-2.11
export PATH=$PATH:$GRADLE_HOME/bin
```
```
//적용
source ~/.profile
```
```
//확인
echo $GRADLE_HOME
echo $PATH
```

# Gradle (STS Legacy) Support Install
1. STS 첫 화면의 Dashboard 에서 아래탭의 Extensions 클릭 -> Gradle(STS Legacy) Support 체크 후 Install 클릭  
![gradle_install_1][gradle_install_1]

2. Install  
![gradle_install_2][gradle_install_2]

3. Install Details  
![gradle_install_3][gradle_install_3]

4. Review Licenses  
![gradle_install_4][gradle_install_4]

5. Restart  
![gradle_install_5][gradle_install_5]

# spring-boot-orm-learn Project Import
1. Package Exploler View 에서 마우스 우클릭 후 Import -> Gradle Project 선택 후 Next  
![project_import_1.png][project_import_1.png]

2. Browse 클릭 후 Root folder 선택
![project_import_2.png][project_import_2.png]

3. Build Model 클릭
![project_import_3.png][project_import_3.png]

4. Import Gradle Project -> 프로젝트 체크 후 Finish
![project_import_4.png][project_import_4.png]


# Run Spring Boot App
1. spring-boot-orm-learn Project Context Menu(우클릭) - Run AS - Spring Boot App Click  
  단축키 - alt + shift + X B
  >에러가 발생한다면 build.gradle 확인

2. Console 확인
![application_started][application_started]















[install_git]:https://lh3.googleusercontent.com/Cp1Ad2MQoMwbQ7jHuucWCuTZcOkIqz0Z4NDbexA30F-Jj77TswZuoQAks5Bt39H80XT6ysU1osKlTuzoVMRkG_4OLwGx-UkERXEYd5121tQAI7pxS-FA7Va7UCsqs_cg3-jTTZy4BIwTYCYCdT8QYq5KcrI_vCdz2l6bpjWmE36RPGshbgiJJc_fiC5qoP3pzQWr_WcMuAIYV00-IljiRTx3ZQsSKfEzL92N5WwbO0u73mrHIXHMPTqLMRoGak1ktlJIqcIF9-IKbSTzg3YAN5Aip00DgSURJ8xr59Z-LiQKA12HTvUayvdDMsdFthdmNLpYnrWApbQiMFyqDs1smd48jJT_WtkVH7FS5xzzkirgquQwp70sHHI31Mxg8vkKlZV3DJ5JP0cfos7_7dox6krl_ipVaQY_IkPwOM9310b9F2jjAxPQTk_EBf9FYuX3DfuLeIeYcBJPd8j_tYqZ5xLBf6KOfRavD8JymlTQMBaJJXwOBXijg8gWEkxB9ROVtasZsRF3MUhwVES3GaebbQOVIqxPgAtVH64HicM4OYVeWZx65IQlfXF_bJgz8CvpgZLP=w722-h462-no
[git_clone]:https://lh3.googleusercontent.com/rvLIe1E-Cyywg8xFGzDJjaG-LatBPW2yw8UBAZgDlj1w-6MrI6d5PmFh_zmAvhiaY23tQgarS2unIsWHfwtuAI20imHH-CK2jBV0XNu8C5rEDozznQJG9AQ5QoR6Gib9GvWNOZf-pXz-R7TMEYJ5GGNOlc33LOXNuXaEJHA4_ahg0m8YYPteQP-KlU2Y7S2LLxCmzhLveFm2C_cSDFqU-FzPSVDuj6JSsWKXpz2ZRDTXAFFuG4REfMdT9ww1Y4CedNGyTEdUb3U3wWUtTlVr1FIgnfHDHzENE6aQQjEfnKWliasbLak8rpprTAs4JWH6BnC7j19xa5nXVka41ELx9G6uxYR1rpI9aj51rPkQKiAKzbULQqXTTjFx12PgwWPcG4kOgLY_cBfVl_Yji91QI7N0Cmk0-ZlSl-qHMIgkbsOTBuA8QoQaL10Btc8MBy7hyWBOZ2MRsAFwvMdAl2qc8gbAhMncavD_XdPYb98O4bIan2OtACobbC9I-18ILFQfmbg-mz0i0yUAp62qBuNm6amJoDesszHKCaQY6bRzuvYJd7PhASkHUBEp1nQz2wtHLJLG=w722-h462-no
[sts_download]:https://lh3.googleusercontent.com/KDfw4_uM8mOHOLPf6heTXRK2QqC5FPj1yfeNr0yXgAVUt55Tfmc0V8P2rnG9DiDccfQkJRyESuMzEQQ32yZ07Ot4Ut2P2JVPyWNJw1s-NUBLIIDrN4PU9G4S5czr_IFiP4t-xSBMcyAPQuoTLRc6rqGoHGnc3L-38EoCMT87NvHMZnG5op-Jhvn0OiVGFLv2fwzPNuo9YQhanZONsBKdGQ4lJN9iKEAY-uFIfHFvMWfbf42R0-qiQaB42ok8H2UhRdOb8VlhUp0fCVaKZoDKC6PsI2snTsVBUgSb7idcGGKKNkOtxgFx0SD8Bp4o5HHT3HSt4kA3x58WSLCSTj1rIGzTbSpq4WiCyFn8OS9O5o_Bw-VfQshP6Bpez4S6iCcXVz2YT9oPeT6RJZJr0Dh1-V-9U8bJBAm4arO6ktj_C08xgC3YIdbYQ3rHwtSimxjn5rqlsHotVi2nqT_8v38uWSTuI7fCi6ijz8-rjBDTJUnQOV5hMO40LdzdLYa81t-9sMBTjt-Z5J7mCdlTN-82GlYjXcoLSeaD_qmmEwTU_qsnckdni4scZJNX2FDiSoTnKwn2=w1041-h602-no
[install_gradle_1]:https://lh3.googleusercontent.com/DKoJeYCX4nMQ06xL6mto6yBUVLW14JDmFnovHFDIOpRVqkEEpZNezSJcJ5hSIFfLV8z0iKgvIqpd96B_jdvvoq7I44etWeEtGbdu7Ln3xcIwjQLJ-RL8R4sMFNX5yYowaljUGF45xWkRxqeMiwL5E1dJUYC_nhERWqLsf2SNeEA9R8Z6XBPMg4_geLoBcrzLhYT3caPyQCiNVJ4t-pJ6UuEWNxJ_ba9OV5aLkDvJe8acrAyxjzvroVNMJsYYAzFhhwMXQP1Dz9BnXjDJwm7xL7IpEFfl7b5_6I6nUnwYlNr0lA3vGSA3d1qgmv3wGmJnAAUQdP2h_hq3a165-LZEdVK3SJL5ZhWrvX3tyKehyW1mBteEA-uqz_QXBWf_YdPsWyI-_dLdEhIzbdYCqQ9sRCj6bugyV6n93D8I7I_OINHdX6EbsFCY4tLl3_-yH7scZbATXsYCd7ndVmLj9hp7Ksct0wk4M2gC5u19g2PfPJdxX1Fqea5RPxBADOu--iQThMcG919SYbVK1lUwmTynOJGsMCSMUea2a3GZ342ULdaoNr79E5aDLmcfXE0umYpfLVNd=w1819-h742-no
[unpacking_gradle_zip_file]:https://lh3.googleusercontent.com/ImMFHuMlsRh7heTomG-_V-Z37JNnMQl3B6FEB9LkuEJLt-vzmXjdiIge4Xx0DLjW1TIL5g5BtK7HjmOMPBt-NJjZNd_mayuVBd9xR_2zM7FVoXLLmP3wTEqNiX5oBknwHEmfEbpVUKQC5oZUfPqFN3tT5EOEHyO1gU-elotF1kCAvlcxiy1uwrEvei6GCCKb60P1yVG8asjVGbOhb3b7QiG-e0tfcpDVwO1YbB8sJfkh0qTKFV9LE1XXvmBxoGL3etc33rbqmGm_IyRvqlDZUqI7Vq7I7q_wbdGEDjqfFZrihlCDwtrBRu_Nfv3tpW-Vc5rfGHD07BzorR9UVirKcYUbLHKtBuK9mfSDe1B8kNK6NsGn_BfKrDikkMRcMmO8xpEaO0fhKDJQBfoHGiy-ITT8fAV-ZcoTL0O-pM25DGMmWelDm-21PdIxI7FaQJLYi7jGQQg6cAEe45quiqtbGQYyX5LceJJI75pHmFJgemEOr4vW7-Nx1Gs38oMVUBbBv0NMHcTt_q9AmVh5anwy285oyHYwpBOheHZQPDNCFcX1Ejk32qiP6YW7sFWxn_FCj32u=w898-h766-no
[gradle_install_1]:https://lh3.googleusercontent.com/cmZdHTQKuIntaA5tekkRK93gjNSDbv486jh003Z0FGBKIUAqNpmIVzXyQ6LwGr1VhUt-uBfKJ1Xpuua0YaXTAOTt-AMeHkMI1gGJI_315NcjcU-M4dXdNXyTEQYNqbotAnDcu5qBqqitKdvr9ptzPyYdmsoywmBe-hBOC695aLk0Cv57s-LpS86wanverRCfRJn1ExDgU16vhXWKaAt0nkBHu4FRFsRm7gNhVTjuEZ9K0s7jwj3fqirUjETcwomxOkB1lUcyojGQzp3iIFBQyP0_A1Yt23DZLc0n-2kmPAacQD_-0wOBtJGvIU35VS3AA2eX3joXQkRAYzaMnwN9oWSswZUJhZebiiJQGOB1CySLLZPHA4rCdMPzbWTUWTXMDgopAfI2NiyWkqogoDMp8Ars-ZPCxrUb3Is5YmEnCYChDySKC-9453O-_Ci0igVXczx-ShjxhL3ZJ3M0apOh_Ay211uz8uIBov9ehcgIT65prJYV97Z_qoJfvJF654Sf-TCDTRAmsfoC-szayPrvDMaceGyuh0lpcJvU5MbxwSJn3qHAcgPhrnLApmVcmDlV3C-u=w1101-h817-no
[gradle_install_2]:https://lh3.googleusercontent.com/mABneyZ9iiEuhSeV5YT_ThHAL5gAXjVL-1aeNrz_sjzEG7vwajiPNzTO7QTPgz0ZlKwq6EtNQRIO2HU1uCB1ojrkw6II6nBl-7kdyGtwvl6kWcs-HBGWjvbC7Pv-u-dcNVnjpYs0f3TCEg2CbYBJuJUMEtqVSZiSv49_SiE6R2QW83y9H5079vA92XDi-Qhg3nJmbyUkLw4WQoCw_xe2d-qQR626IF90k36JV-BKu9fw9__24W2bNotRN5zFMaZvkbjBQbGIlulaJvGpf17KUfo4wQAPY93nlGtZAtkNOkjGmW0qD7qbxSQWItC1xXvDXTyh2McpW39ffIdIZw6c7mETReaCFO1Ns-dlW69_6KMHhXK0t3gtBouUhiGLvd-S0bfSX7aYqdLZpUjVLQik2lexQnHV13oq1CacbaTEMzDQ4MhHDcTtq3lxBN8Mflm62spBKmM1h-qfStRj68my9dWAI8ROjgtT1_AoyNppoUQhCRf9tRHNVzMWTz7BNhykuoGGMaVSyCwnucO5g4ALP2A5dTlYsqDzZesTvvZQZHUSOD52rCit44InCdwGMptnwxLa=w861-h611-no
[gradle_install_3]:https://lh3.googleusercontent.com/f1CRVUAQ6sQHXEz-WA2BrO5e4biIXj5_3vTaqbbBIvc_puMbuCwJA1EFA0gKEpiq4E7tdGpxb8NHWfiXQORrv8AhP0GYztijQBOK4X2FXYVlO2QV3k6kzu8ETukBP4-jEsETZW7LaPBAraoX59ky27deYVohC0etAt98ofqdg_6lDqx_y2CGf3idLeRcJ6Eu-J_fLNmfQe-NnEJZ7QmFv_4LSlVJjQvutKXmsS05wPTwMuBmKnu6AsvybmsHazLxmuHeFIhtEobBW0vlIswLxsvmd82xiiw9YTtDUYgKXv84oZxy5ml4GozzTL5K3f2A33hQFgyf6whstV5lptKYuhXTlf1iiF9E14EooY5xfeWBIjUeg8HcQ3-dwSb2uQZ4zjdQnXKgy20ye8PZhgV5yLOnP9VZksmL6alvQx60TnqfmHULtaGYfZmiyfWiBlN_HpO9rMDXekrwwq4oDXDThLUiWsZkt_efKZSlMTZzu6SDycOfXEiITftNZnbPi8AhZkBy6TMZbrSe1sEx4KJmI2jcgUk4oCXAyBHnx1bAmpi2qdr8qDMA85ngyT4C1SnRMISK=w861-h611-no
[gradle_install_4]:https://lh3.googleusercontent.com/osmq_aNqajI90-g0-A3bs57-1undPVI3EC0ywJpWL7tbskMYhW74yX2AYobjQdsiacu9_Oo0U7LBXURq87tE3jaBIkHlzPmHcglJ_HqbrzXKRfNdIWWV_9181I98SjNlHr3dsGKU5YmZ_fnOQQiEDbcAmwFnzl6F2jA5O_l3_h_5ovaOlcHTiiK4Ixk8Z8ED7m0BxqT-NemfXJB90WTkup7apy6j-9VemXdPTSmqr0U6Ad5ZQEJpGmrwNQ8qZa24my-_BpdXDV6we-5-EIMjlug8E6KSnmvYB5kVG-kOBEJROrJV78K19sQtmcPAODSJXzIjkabCV9x9AwmLXrFawFMw2Cey6sNQ7KKCUuGuo4BuFquKB9BMtvS_gm31gccwHltjsY4n8mIgKjfzixaqzX6AyjuYU-vwGKXT7x059tBxI7eeFDhBEh3AjU6CXuTgnK504rnxFbsgjw5q2pEcfYIyxSr0MrkZlW8cBY7S6F0JOiiRSYNfrZkLU179fiBu-hAK60F7cfZ-UscN70KRc9UusbpUptHhueROqw9NkR-7qsvfkTQgk80bRb7N--VXqv9E=w861-h611-no
[gradle_install_5]:https://lh3.googleusercontent.com/MSWVW2S7Y1MO-Cp-jVYrc0UgJztGQPIlCkDuS1FKgslvw8yEcZkR6sYlolUNSHnyWY9aXxsdOlrL5DCnYJSCkxmKD1h_u7Bn30u4J9qt2PhX2qlPFnP6d_fi-IFvbBQ0cKEB9waKpXCuVZq9DMjhxbUaYb5CsexiRR9rvHZOafv4LArydgn4drDNYmyIBoxmvqmS_AGhiwdDEO-oCyOTbyRDa1Z-QFQ__AaSAQpYsJospjgC9kNLsM3N4_iQ8bBotMjMljHtWFwYVQf2nIGrLkwpK3TkoVDqmYTjLPM-LoM7cZDN_HrYNXpVLozJBCmuGAaOGBBMBEDnyu3khj0ATB_T8pqA2IyjtbT55ewoXwhV5YHXOZh5h-ILUdLJ3iWVUHoWM8ADiyTDmxXhRSOBfYtDOn_Cc92yi-6Vw0bolB5KzAix-M8DT6zs6FSP5aCW25Wsdeeq-k24P3wFmEDq4eFswZFARRw5CM_ek6g-KcfdlxK5hv2pmwxkFWK03_FnBLyGpbNOl54Xp_bgw0jHzWIP8gj3cQBQYiCYh6er-gSeJz_cntWtTFEzYvyAAAoZvoeN=w611-h170-no
[project_import_1.png]:https://lh3.googleusercontent.com/lxmaheKqidc6eIpC6XNtxJps0czJ78y2JEJTdeOcwzmUfIqYQVzmF_Bfj1Tv5afKiX22eKmMZ0L6BcEWOCXlmvmrUsO59edCr3HY_F02B4AWt_rLS_iMFE8Q13c2BxjuFk6wEF9hYWM1SRxLdhcR8zSAM2rpyAdHFqgxlMPi95J2jb9q1Gar_bWr8pl-rVOPqlkIuMOdrP6LkkvAhSNh6XGRNliInEmwbpJC5KnLi1VS1SnZZvhsWQkrOR5vag9I9x-gvh5lW1i0hjhyhbarrrxduYtHyYLB_-5UuYMWtzhgePNxsu-3vSbGYCEpnpqmExWQ82KvVW0QP7bcgjJsJs-rQNFpSeqyfJeXtolIwE51DNfISB7kFs8FOWb0rnKKf8HuriEcTIaAWfHfdShQtpkugZQPX2n2l5WZ67hNcw7Vx6FjAaN9fAL3XRkDpn0QL_zGkWxDn6Hj3C3g2znV9779od2P4wRAwOdBZCZKQ9eAFPnLa6bkKbpbDR3tB6bJZ3McD0TGl2dU20Kxck9JGhI9f0n_ALGk5etE5mq-IacgUq2eJEsAba3MoFJJFDak9bPI=w607-h549-no
[project_import_2.png]:https://lh3.googleusercontent.com/C5s7SmUv2F_e9w4TxAh3I0vFT1df3p9_asylbAU-vWUBNB-cf22vfRvMHfKGieTFJ3tY7LCcPSSG09-ISiosxEhJo2w-85Hquz10MWjeCjt4LtcYwrrAdVVkUDXdr6QAXvDgSv9L4SMCgfbMlj49NBpPRCAhdGOemNysFpvUiEnDLii4l4QMcX26jGd20NsUDwAKOgDQHd1Gi4JN7MYw_qf2az3vF6itsa0XO2rNBklysPrvdVWFcZFjAhLc3ul5ZLGvYqA2INiYBZ7p20AGPh4keoBBeHHKrdZgMlJWd-vSG1KADNs87C8np3EaO54YWyyJMqsv89pmw0sZXtXi7mjgPdEknNdiZLadv2p1DfXiu3K2PiRSkw4dYm6DG5aHKDqGENyFNRSeARtSmorY_C-L_UmWW3LoPCgW-W8aiHJyTbpJElUdYIPSOHPFV62OeiLO1K1wiZ5uirLSnCnHspxPTr6Lsrxd4bMZjBW1ENaDFR8YYNPsp3geJLpdY6SqlBzvIoz2sUnhQHcRQ_dU933DyEaYNHFeSxmD4NobEdMK5VfKy6FQPKb_nXoqDTjlMV-q=w711-h779-no
[project_import_3.png]:https://lh3.googleusercontent.com/e_6t2r0BvdZY7p6CpeiBEo-on-7DHYXaZtZ1105tb9BdGwbr3PGSUzCn6UzCNq2tBHm3u4GbwCewJGaCpVFaj1q0THxBUztoxjVH6wEI3jZ3aLcFt4_B3hZC5rky5hv97dqrE2DihCfmKbSZoEF_DkCXRJMgdbFZG14d6fhXt3QhRzsqaPqxHeVRu3YYF6Tbk-KssTkNxlfYTtdQID3mXUlLCfegTG4CA7lhVOSquxe7H3QuKcTpo1RAGOklV_a0oCr1i7oUx6ey1GroEme8yop69i2NjtilNOwxZ3hOtdH2LaX8VS5Ca9G-xHy9UfFqmyoNOjXna5l5efusTcGgaEnJFJ1Lzpmr-xaQIpX_ALquZ7HsegbOhUosIgsqAcqvV8YH3uznLakvCfdrE4DXsg-z0uawXDtvWvExnMJNhUdnWbaBEAmVCtZOgw3pQAMK21nWsdYmYEFfOx_Qpyf0InnBUxbUp0x2hsn_aEc11KTPLQmS0iSAxj05tgf_FxDh-kZHMs4Co3HOMJtRtLKzO_jZko18p4Jxtx3YCl3q5WM2-h7UVhV0uy28PHOOwKzUSafp=w719-h783-no
[project_import_4.png]:https://lh3.googleusercontent.com/QFqZJeLyGStpR0eGdrpk_7v_-v9R5IeJx0s7AYF5I_UiRdYezBSSM6l8G5dHZAarZoXxWGHFuWB-AyRggsbvjs39viUpCExTRYgSaOhhu7KJ0OFoyGClNINq3j2p4mAG8Pv6TceBeWCdfAKCl8pn4QKnkdYG22kBrUbmMEzAmudyS8ya7-xgQIhlCFNdwYrw9sK97zeWPrmTSiBJ5NLjBKmYhAg4Up--3GJkNVzCu8HuweJ0r4rKdYL-Xj5yLG6VAskNptF2erUIV_hG4P-OgRlScndLZz5n57Dpl-dIy-t3doBYO3yPGmxPUwX316XgsQSa2cFSNFxUKC3NT1MFRG8CSh1J6y7lwCmJhTc4y9zglEr34QuRwt6NREvU4Ve1ODtl3FGBSGOI_Fs3UTXiQJi4yrum54XLqhSNqc-c3N_dQfcJ411nRX0tTz4rTGtC_WeVSEyUMEob4N9CbkaoRBO88uoo_ysLzPQtv7X-vl-Mgclk-qYClLDA0OgzUp1bKDsqR3ISI9ppNo-eG9StMRh7OrLd11IfqdydWqV2_O0_oVVGOWMXLcXfRNIYRIjL3tpv=w711-h779-no
[application_started]:https://lh3.googleusercontent.com/pfxdDZdm99GNFYPP23pcjnM1C77sG2cJp47saUd61Tdy1JNf9_xP5gJgBzMZKy9No_6hBst-7Tkj9qJk6HxeA4fX4RsWW3KqxF5Ta7QW3EchEUZg6yySPDixyYv9H3Pi4mmI2GDiemR1Lq7wcTpiiiEu4XtMond9sHw3QOr4tQxRX-f0_GEKtNONoD8tI6zW2jp9nXM6zwTelIuLoGrIl2lt5Yr_nmDZEEcuxRbr1C0ZOmmPHL1Wc1A20cqXCmCQkIr_mreRD9mAH7kiyrzd3iDN2tlkV8kqB7HGA0kow8Gr2mkSpJ_HBxdKQ2gLcMeE9XEMjuKdKYlAq0_Kw0OCCinB2JIOLyWR9HHCfF6cLVGM2-PeaHaJELe709HRiwZjVIdhs2W72VC2ydejvb3KP4NRmY6mI3gaKCoIF-R_6jxa0a3992hOQ5EqfT0DsIHN94GhpJnrA4A_xomUwlQTiU7jVf8yiJuWcnk-J3sb46f5U7Qv3G6o_I46e-8mah-wl3ryar0fJKtbChykUq5S075EWkXB9MC6I8u7fOFb41Oo73818YN7daVKdQRJX9H38hNP=w1434-h961-no