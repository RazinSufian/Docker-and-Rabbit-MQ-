# Docker

**Install Docker:**

```bash
sudo apt install apt-transport-https ca-certificates curl software-properties-common
```

[https://lh7-us.googleusercontent.com/kA-kWmYuKFe8umoXkuQoVUf1IvV7bfqlvQ8NDRvPpbgz_OpUAkujafu1Qhm5tqZUFXZiRHg4dpihjZKZ_FxxxcJm_qx-VqDRkbWkkvSUTJwGEU_8yAjvOC-t6wB5ypTYDxah4Ul5P9p_zxMNvDlQ3ik](https://lh7-us.googleusercontent.com/kA-kWmYuKFe8umoXkuQoVUf1IvV7bfqlvQ8NDRvPpbgz_OpUAkujafu1Qhm5tqZUFXZiRHg4dpihjZKZ_FxxxcJm_qx-VqDRkbWkkvSUTJwGEU_8yAjvOC-t6wB5ypTYDxah4Ul5P9p_zxMNvDlQ3ik)

2.Add Docker's official GPG key: 

```bash
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -\
```

[https://lh7-us.googleusercontent.com/2MGbO7pTFNrrljewMJca5yyvyGD0l1jDFQNqLI0DuMqUuNMPkgPhwcizmHVXmmzFcsVhM1ahm7eV_PdLnFTednX9_i4EUaLrxYL4WgEg6vWsEsHBhlikiWsMZXL1PsnPS3aF_ggAEq7JCCyhOmoiOaA](https://lh7-us.googleusercontent.com/2MGbO7pTFNrrljewMJca5yyvyGD0l1jDFQNqLI0DuMqUuNMPkgPhwcizmHVXmmzFcsVhM1ahm7eV_PdLnFTednX9_i4EUaLrxYL4WgEg6vWsEsHBhlikiWsMZXL1PsnPS3aF_ggAEq7JCCyhOmoiOaA)

3.Add Docker's repository to APT sources: 

```bash
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
```

[https://lh7-us.googleusercontent.com/G765n8j_Lve2BRmhG9E5O0_mCtDXWMurMZV2cToYNr2oz1lLlk0xmDtPJ5eCJM1eme9wSMmTJp3sNxqDFEcjkxcR7x_iabvUfJ-WSo7Nv0IFGM6IGwL7MV8mDwLh74ZiGc72fUvqn9SOtI3nXwEJbWI](https://lh7-us.googleusercontent.com/G765n8j_Lve2BRmhG9E5O0_mCtDXWMurMZV2cToYNr2oz1lLlk0xmDtPJ5eCJM1eme9wSMmTJp3sNxqDFEcjkxcR7x_iabvUfJ-WSo7Nv0IFGM6IGwL7MV8mDwLh74ZiGc72fUvqn9SOtI3nXwEJbWI)

4.Install Docker: 

```bash
sudo apt install docker-ce
```

[https://lh7-us.googleusercontent.com/VKc5hJHuLRVcVeR1GAWf064Ab8rfaMYUZODGksxTWSDLP5S95DPVrWy-oT2I5gGvghnxlPn0_hSqPX_lKPyDPddra8GSHvYnsUvZGUX5P7EUkzF5u4V6RZ2H2CiQXdhrpJSiyLPwlpxseONEmTDJhuo](https://lh7-us.googleusercontent.com/VKc5hJHuLRVcVeR1GAWf064Ab8rfaMYUZODGksxTWSDLP5S95DPVrWy-oT2I5gGvghnxlPn0_hSqPX_lKPyDPddra8GSHvYnsUvZGUX5P7EUkzF5u4V6RZ2H2CiQXdhrpJSiyLPwlpxseONEmTDJhuo)

[https://lh7-us.googleusercontent.com/Tr6T07m8J8-CA2dLHtLd7tkY9rcCRm-jnKWDbWE_vZ4MXkY11SOlsFGoxKPcgH43o9KZaK54fQPFP4XnoOitjhI5tsMjFuimKrt_OdpUnnQVqg59YuLbjpK5COUJoVRgH1x5X4vOG1xxf3iIY7xeUuY](https://lh7-us.googleusercontent.com/Tr6T07m8J8-CA2dLHtLd7tkY9rcCRm-jnKWDbWE_vZ4MXkY11SOlsFGoxKPcgH43o9KZaK54fQPFP4XnoOitjhI5tsMjFuimKrt_OdpUnnQVqg59YuLbjpK5COUJoVRgH1x5X4vOG1xxf3iIY7xeUuY)

5. Add user to the Docker group: 

```bash
sudo usermod -aG docker ${USER}
```

[https://lh7-us.googleusercontent.com/fGVSn74z7p3TxAYVAC-rBxNn3mqngZcoJ4HETd3gvKayYcmTp9WKeQ7lF29GtRjRaK5EW_3OMRHWQ1vNoY8HQ9LcoCASfJwF6jv36cGHO1_5ShjOZJs0PpTR-ki5-SoikLoPrc5bCELnk_OEl3WRdRc](https://lh7-us.googleusercontent.com/fGVSn74z7p3TxAYVAC-rBxNn3mqngZcoJ4HETd3gvKayYcmTp9WKeQ7lF29GtRjRaK5EW_3OMRHWQ1vNoY8HQ9LcoCASfJwF6jv36cGHO1_5ShjOZJs0PpTR-ki5-SoikLoPrc5bCELnk_OEl3WRdRc)

**Task2 Show outputs of basic Docker commands:**

1.docker search: 

[https://lh7-us.googleusercontent.com/j7i4R-vKRL-DMXbgrPkqfrznckevQybtMFvR4Yc280TlMw_w__3yiUTREqd5pEfqxFAzDLUTEKCNwaOYD9RRsEQMl6IhVA6wktU1juzTboqDm7R7oXCjFdLf6EUEfHCvVR44pVjKoGrYSH0pHeYm1jo](https://lh7-us.googleusercontent.com/j7i4R-vKRL-DMXbgrPkqfrznckevQybtMFvR4Yc280TlMw_w__3yiUTREqd5pEfqxFAzDLUTEKCNwaOYD9RRsEQMl6IhVA6wktU1juzTboqDm7R7oXCjFdLf6EUEfHCvVR44pVjKoGrYSH0pHeYm1jo)

2.docker pull: 

```bash
docker pull ubuntu:latest
```

[https://lh7-us.googleusercontent.com/zMi8UPbtjnq0jKVOL4zK4lcNAQHPoHRgO-Ayz_3NSPhCslJxjgTjK22_fHrC-tJLzgucaWdHsncoMYcbZVF-VZRbZ3d7-n6o8Z7ezw_yPW1mfo1f-Qnl9YxRAe3kKejGp0HiRP9f_KWKcGVZQkGsZAA](https://lh7-us.googleusercontent.com/zMi8UPbtjnq0jKVOL4zK4lcNAQHPoHRgO-Ayz_3NSPhCslJxjgTjK22_fHrC-tJLzgucaWdHsncoMYcbZVF-VZRbZ3d7-n6o8Z7ezw_yPW1mfo1f-Qnl9YxRAe3kKejGp0HiRP9f_KWKcGVZQkGsZAA)

3.docker run: This command is used to run a container from an image.

```bash
docker run -it ubuntu:latest /bin/bash
```

[https://lh7-us.googleusercontent.com/qqXXA3Bg8psDEpClGVfKqzbBZl1-Ig_f3bwizbYZAiwv3-n_0l_ZKoVG0q-08yrwJyjgFZPUeQ1o7MNusbQ_Sg6fySkwe7xZyBOwD8ZqNea5xONk4MmPc7SLHTpRDNthfRvGmIdLl7F6x8BrWoJiPqE](https://lh7-us.googleusercontent.com/qqXXA3Bg8psDEpClGVfKqzbBZl1-Ig_f3bwizbYZAiwv3-n_0l_ZKoVG0q-08yrwJyjgFZPUeQ1o7MNusbQ_Sg6fySkwe7xZyBOwD8ZqNea5xONk4MmPc7SLHTpRDNthfRvGmIdLl7F6x8BrWoJiPqE)

4.docker ps: 

```bash
docker ps
```

[https://lh7-us.googleusercontent.com/fXPxbzhzdfv-u9LBrzERrEQdW2E9Vl12xNTQZJfDiLSIqb8IO0MpFKAHH7QyXyufz9jgXdIrBugoN9stQ3m-gc-TEPXNobZyayy4hBgpEURPgrc4I1g9xaI7aez9zhSZj9hj3deyDI3v2OZc8earYiA](https://lh7-us.googleusercontent.com/fXPxbzhzdfv-u9LBrzERrEQdW2E9Vl12xNTQZJfDiLSIqb8IO0MpFKAHH7QyXyufz9jgXdIrBugoN9stQ3m-gc-TEPXNobZyayy4hBgpEURPgrc4I1g9xaI7aez9zhSZj9hj3deyDI3v2OZc8earYiA)

5.docker ps -a: 

```bash
docker ps -a
```

[https://lh7-us.googleusercontent.com/3sIoiuG18dLe6LtQyx6z-nSMBWB-d068utJqNSXm8pQADthjoQjgsQVJaETubpcVB0E1umTzKl3nt_MGt_KTBzMAVElTdKQ1v72kbP7gVUxQZlO_k5EXu8NiUYCDzRK3YFiD-KvmVZOptbNgaM042-M](https://lh7-us.googleusercontent.com/3sIoiuG18dLe6LtQyx6z-nSMBWB-d068utJqNSXm8pQADthjoQjgsQVJaETubpcVB0E1umTzKl3nt_MGt_KTBzMAVElTdKQ1v72kbP7gVUxQZlO_k5EXu8NiUYCDzRK3YFiD-KvmVZOptbNgaM042-M)

6. docker commit: 

[https://lh7-us.googleusercontent.com/hfrhB6DFomTq2OwzF3jGIK324wpiaK89xHMvruEM27oT6JEmekc9WHQJFwJUozLE84sg5R8XMsfD1qj8K7NQslDxGUCLFpnmCk4w1CedvL0xGq0Yq4PDZk031weSWjvTeG3jRJUDVISm63kqq9y2KZI](https://lh7-us.googleusercontent.com/hfrhB6DFomTq2OwzF3jGIK324wpiaK89xHMvruEM27oT6JEmekc9WHQJFwJUozLE84sg5R8XMsfD1qj8K7NQslDxGUCLFpnmCk4w1CedvL0xGq0Yq4PDZk031weSWjvTeG3jRJUDVISm63kqq9y2KZI)

7. Docker rmi: This command removes Docker images:

[https://lh7-us.googleusercontent.com/Kv4IKQtETLDPQUVe9VbMC3Zftidi1x5MO_wguB9Wx6L0711MGCiXySD1Phlfy12mXFJdWNYogEzK6f9KM8ELlA9tgJyKycok4MW_Ix9Zxu68rraJ4es6HPHMKlMaSH6QxDJHUKfaIOf1Jahrq3-ptCM](https://lh7-us.googleusercontent.com/Kv4IKQtETLDPQUVe9VbMC3Zftidi1x5MO_wguB9Wx6L0711MGCiXySD1Phlfy12mXFJdWNYogEzK6f9KM8ELlA9tgJyKycok4MW_Ix9Zxu68rraJ4es6HPHMKlMaSH6QxDJHUKfaIOf1Jahrq3-ptCM)

8.docker rmi: This command removes Docker images.

```bash
docker rmi ubuntu:latest
```

[https://lh7-us.googleusercontent.com/htN_B0EuWCNz0Zjaz-INDujF-H4lbN0dnHx4mzaUsHbg_9qG8vPBI4c-HrWKacfMsCMb4kKKag9nR53oTFxXffKa638UkptaVHzF9qrTsBzdvNgwhoQtCsnjLQQBnCsi6116fvthIqRqSbA7XJ0qPJA](https://lh7-us.googleusercontent.com/htN_B0EuWCNz0Zjaz-INDujF-H4lbN0dnHx4mzaUsHbg_9qG8vPBI4c-HrWKacfMsCMb4kKKag9nR53oTFxXffKa638UkptaVHzF9qrTsBzdvNgwhoQtCsnjLQQBnCsi6116fvthIqRqSbA7XJ0qPJA)

9.docker logs: 

```bash
docker logs [container_id]
```

[https://lh7-us.googleusercontent.com/fBj9Kvd1n5OgauP2UByEZl4_lu1Mru70aBLru0hU0p8y-GGW8d2jObPTuTIYmZMs9Xfr9xtR3-1PvG2zPQJraKix6M-9_oHWSIJ27gX_fu-MDRz_hXefBvDEaNKsEEHyIhWuuvMbh5BSfepHRq17QIM](https://lh7-us.googleusercontent.com/fBj9Kvd1n5OgauP2UByEZl4_lu1Mru70aBLru0hU0p8y-GGW8d2jObPTuTIYmZMs9Xfr9xtR3-1PvG2zPQJraKix6M-9_oHWSIJ27gX_fu-MDRz_hXefBvDEaNKsEEHyIhWuuvMbh5BSfepHRq17QIM)

10. Docker file: to use this command I need a docker file, actually this command is used to build a Docker Image from a Docker file, but i didn't create a docker file yet in this current directory, I will implement this command later and show the output.

After finishing task 3:

[https://lh7-us.googleusercontent.com/wRNWrWWsELvqVarN7E2IHwL7yqWeVtmr_6dI5QhEEhoqphLMMpOWdYaZwhSJqGt0VFcRbUPdbpMEe55Aqxd3l85Suc_8cRQtQVXTqFLehyVi5GsFikTIfKfvuF-P3Jiadzhm3_1kjwobEC7FyjUoKY0](https://lh7-us.googleusercontent.com/wRNWrWWsELvqVarN7E2IHwL7yqWeVtmr_6dI5QhEEhoqphLMMpOWdYaZwhSJqGt0VFcRbUPdbpMEe55Aqxd3l85Suc_8cRQtQVXTqFLehyVi5GsFikTIfKfvuF-P3Jiadzhm3_1kjwobEC7FyjUoKY0)

11. “docker inspect”: This command provides detailed information about containers, images, volumes, or networks in JSON format.

[https://lh7-us.googleusercontent.com/whEmtxKWsdT9zloxN8XgG0xXFAwULHUXGQKEQrLNzcSjH6preLWhF-Ugp0wbG6d2LiFnbkUS7N3edWQ5UBcdhgxf6_Al5Lv-mDI6nKaEFk6Ez6IzC20B5m0yY_udC68xcoLOVlO-XrjrrY-g7-uNZP8](https://lh7-us.googleusercontent.com/whEmtxKWsdT9zloxN8XgG0xXFAwULHUXGQKEQrLNzcSjH6preLWhF-Ugp0wbG6d2LiFnbkUS7N3edWQ5UBcdhgxf6_Al5Lv-mDI6nKaEFk6Ez6IzC20B5m0yY_udC68xcoLOVlO-XrjrrY-g7-uNZP8)

12.docker volume: Volumes are used in Docker to persist data and share data between the host and containers.

[https://lh7-us.googleusercontent.com/gGUK0l57J7QL6_eBo0Ph941fKSGbq1pzrZqeF_Xj4DTdEl3T2-FuGfGBiQ_Di6c6o4mPgctDqXCmPXtcuEZK_JxHFq68J6eVn3xKWdta5dY01v7Oe3EX8bTvYAelB37GDXlzHqLu8sJEEtqF9g7B1PI](https://lh7-us.googleusercontent.com/gGUK0l57J7QL6_eBo0Ph941fKSGbq1pzrZqeF_Xj4DTdEl3T2-FuGfGBiQ_Di6c6o4mPgctDqXCmPXtcuEZK_JxHFq68J6eVn3xKWdta5dY01v7Oe3EX8bTvYAelB37GDXlzHqLu8sJEEtqF9g7B1PI)

**3. Create a Docker image using Dockerfile:**

1.Create a Dockerfile:

Create a new directory for your Docker project:

```bash
mkdir my_docker_project
cd my_docker_project
```

[https://lh7-us.googleusercontent.com/mYhoerNnFbLZnSiPITmxhU-qM7qmHRw8GhcO9GoU9o9SGlCcqNdbssvDzPHc08HgIFGoChgXkXoEKBg_IUlW3C9fMAcKuLFfAxuyi07LX-f7Y17xtGcUk8KjzTT4jpnRX71kaLcFruItwD0AqhTFxT4](https://lh7-us.googleusercontent.com/mYhoerNnFbLZnSiPITmxhU-qM7qmHRw8GhcO9GoU9o9SGlCcqNdbssvDzPHc08HgIFGoChgXkXoEKBg_IUlW3C9fMAcKuLFfAxuyi07LX-f7Y17xtGcUk8KjzTT4jpnRX71kaLcFruItwD0AqhTFxT4)

2. Creating a doc file in this directory:

```bash
nano Dockerfile
```

[https://lh7-us.googleusercontent.com/c7VjHWP3gg75NiRDBbojZtcYyIg_bbkVXAs06EXoSWSg9SE0D8LZi-ukXGKbBGo1v4d13A3dMCj3Z_PtUCIwBwhTgeIg1AM3i5q19y0HaGLssM5KcE5B7guMg6aExr_CuvDmBB9A-lgNbfFng8oehOI](https://lh7-us.googleusercontent.com/c7VjHWP3gg75NiRDBbojZtcYyIg_bbkVXAs06EXoSWSg9SE0D8LZi-ukXGKbBGo1v4d13A3dMCj3Z_PtUCIwBwhTgeIg1AM3i5q19y0HaGLssM5KcE5B7guMg6aExr_CuvDmBB9A-lgNbfFng8oehOI)

Add the following content to the Dockerfile:

[https://lh7-us.googleusercontent.com/UyYH2f0rwrTwDzPC9VhhyYhLxYzzLtI_XjtSBoemAIu0YbfkE7gj0RJSgcpS9ap19QX1cxx77E8pQfJFk67jjpD7dGhPDMxemq1Ehp8JJziYNBGWse_WuWJVd5xtQRqv4RazYphKCfs1j1LnqTbjYIc](https://lh7-us.googleusercontent.com/UyYH2f0rwrTwDzPC9VhhyYhLxYzzLtI_XjtSBoemAIu0YbfkE7gj0RJSgcpS9ap19QX1cxx77E8pQfJFk67jjpD7dGhPDMxemq1Ehp8JJziYNBGWse_WuWJVd5xtQRqv4RazYphKCfs1j1LnqTbjYIc)

3. Now i have a docker file i can build an image from it:

```bash
docker build -t my-custom-ubuntu .
```

[https://lh7-us.googleusercontent.com/pFqLhehpciORCzO4Df0sP171k49ej_lLit7ZAx7zNw7IccGKiVYkoWpIS7Be8aaqHrjsoqXCvmZbAu9NsTq9hDnmr76wrffbT2BYXHfg8F3432mSPSxluXm1roY4C6yuf25QQqISRVJD7LoG-OHaJ9U](https://lh7-us.googleusercontent.com/pFqLhehpciORCzO4Df0sP171k49ej_lLit7ZAx7zNw7IccGKiVYkoWpIS7Be8aaqHrjsoqXCvmZbAu9NsTq9hDnmr76wrffbT2BYXHfg8F3432mSPSxluXm1roY4C6yuf25QQqISRVJD7LoG-OHaJ9U)

4. Verifying that the image was created by listing all the images:

docker images

[https://lh7-us.googleusercontent.com/l6dNCMNSMr3X4i_bQm6-Xc44sXBgV0DNnGB9-Zl1QEsbrWrYKiurtMYxv0bxvz5K0Lg6rYz-UQ47XDkgFFFFiuELX7KH5RsUpaOAIxek8P9PxV3O5fdPBtPCmsQ8LrLgLzz1pahhTWuJ_5Na2Xug5qQ](https://lh7-us.googleusercontent.com/l6dNCMNSMr3X4i_bQm6-Xc44sXBgV0DNnGB9-Zl1QEsbrWrYKiurtMYxv0bxvz5K0Lg6rYz-UQ47XDkgFFFFiuELX7KH5RsUpaOAIxek8P9PxV3O5fdPBtPCmsQ8LrLgLzz1pahhTWuJ_5Na2Xug5qQ)

5. Run the container from new image:

```bash
docker run my-custom-ubuntu
```

[https://lh7-us.googleusercontent.com/HLmBBRq2TKAvQhWKPVyiUNhMtvYLTJtUorX3xsFdCvkR-sgYN2J21-IBcwtYUvjaivfV5axQ2faKI2UbG0A24SpJtdDva1Z42LzucIQ544QXbR5IYTHQ5OOTQc4pz6YzZEeOL6yWBR8evsUs9ty9ylg](https://lh7-us.googleusercontent.com/HLmBBRq2TKAvQhWKPVyiUNhMtvYLTJtUorX3xsFdCvkR-sgYN2J21-IBcwtYUvjaivfV5axQ2faKI2UbG0A24SpJtdDva1Z42LzucIQ544QXbR5IYTHQ5OOTQc4pz6YzZEeOL6yWBR8evsUs9ty9ylg)

6. Now running the container from the new image:

[https://lh7-us.googleusercontent.com/lbNdkuUdOKmKvjOlKO0xuXaycH5wvr9aefV-CpKDNkT4tQ-qya1BAOAiE2G1zF3rVf0hGFdOLCFjZyq3foRkMauqlAHwob2YVuFN0JJ-Tjg_L8CIEniiv4tdnwsT8Ltki9CQ7_Ef1buWrmgn2106P0o](https://lh7-us.googleusercontent.com/lbNdkuUdOKmKvjOlKO0xuXaycH5wvr9aefV-CpKDNkT4tQ-qya1BAOAiE2G1zF3rVf0hGFdOLCFjZyq3foRkMauqlAHwob2YVuFN0JJ-Tjg_L8CIEniiv4tdnwsT8Ltki9CQ7_Ef1buWrmgn2106P0o)

**4.Run a container as a single task, show outputs, and show the status of all containers (using docker ps -a)**

1.Running a Container for a single task: I am running a container from the “alphine” image ( a lightweight linux distribution) to execute the “echo” command

docker run alpine echo "Hello from Alpine!"

[https://lh7-us.googleusercontent.com/61vrzCseg8k8owQZc-piwN80ca1JYB8MGx1TqqGPOANbkNqKCYM5YIsYBQxMfZRl01hIMRc1gAp6k-HJ9KG05h9XcCuqyRywV0ycSOY1qD0z1QhLjRsCpvoY8nDbkP_NPIxvSmIlRp482L1eYfab-Rk](https://lh7-us.googleusercontent.com/61vrzCseg8k8owQZc-piwN80ca1JYB8MGx1TqqGPOANbkNqKCYM5YIsYBQxMfZRl01hIMRc1gAp6k-HJ9KG05h9XcCuqyRywV0ycSOY1qD0z1QhLjRsCpvoY8nDbkP_NPIxvSmIlRp482L1eYfab-Rk)

When i run this command:

- Terminal pull the terminal image if its not already present on my system
- Start a container from the “alpine” image
- Execute the “echo” command inside the container
- Displaying the output “Hello from Alpha” in my terminal
- Exit the container after the task (echo command) is completed

2. Show the status of all the containers:

```bash
docker ps -a
```

[https://lh7-us.googleusercontent.com/FJ7rnV5ke_iYI1Cw-SVWKS4fLgcTGRMClXO1F_0UFuWIo3ycts1Us0RMPJbrx0ZsRiEMKcf7EvZiRhdeyRnQMDu_QpA7rkPoqDRG7Q0ACSsm_9FVY09ZXrD7aX_WriFm8vlj_Q9u6-zX5isEvtT0kcs](https://lh7-us.googleusercontent.com/FJ7rnV5ke_iYI1Cw-SVWKS4fLgcTGRMClXO1F_0UFuWIo3ycts1Us0RMPJbrx0ZsRiEMKcf7EvZiRhdeyRnQMDu_QpA7rkPoqDRG7Q0ACSsm_9FVY09ZXrD7aX_WriFm8vlj_Q9u6-zX5isEvtT0kcs)

**5. Run a container in interactive mode and install packages:**

1.Run a Container in Interactive Mode:

I'll use the ubuntu:latest image for this example. The -it flags allow  to interact with the container, and /bin/bash gives  a bash shell inside the container:

```bash
docker run -it ubuntu:latest /bin/bash
```

[https://lh7-us.googleusercontent.com/KojBE_Q9IeegaS7WLZT0NJwhlf1Il11nglFj6b1pq0C5seF_FiCrVpgWUaaCCBeOkF8_003AmzY9IUnQdsVcapGHgwvNYDuLF3ZjAqy3tZb91bJpzfLWUPFuGhr7SK82SPy93ovKMKB2hrB_NI2m7P0](https://lh7-us.googleusercontent.com/KojBE_Q9IeegaS7WLZT0NJwhlf1Il11nglFj6b1pq0C5seF_FiCrVpgWUaaCCBeOkF8_003AmzY9IUnQdsVcapGHgwvNYDuLF3ZjAqy3tZb91bJpzfLWUPFuGhr7SK82SPy93ovKMKB2hrB_NI2m7P0)

After running this command i will be inside the containers shell, indicated by a change prompt.root@container_id

2.Install packages:

Now, let's install a few packages. For demonstration purposes, I'll install curl and git:

[https://lh7-us.googleusercontent.com/oC7tZhHAHNz8uDSZ4hY_XIMHp9TY0Kxo2KIcSLgOPvB6fVzL6OJyAy_ydZ36xvZCU9oaHXjl63b1yG6_dPYLa49iw8MABB-dhvxfJKNGov7MsfZay2tdx2_iP9pXRx1qo8sBMVXdXdWMzArgiS7VLSg](https://lh7-us.googleusercontent.com/oC7tZhHAHNz8uDSZ4hY_XIMHp9TY0Kxo2KIcSLgOPvB6fVzL6OJyAy_ydZ36xvZCU9oaHXjl63b1yG6_dPYLa49iw8MABB-dhvxfJKNGov7MsfZay2tdx2_iP9pXRx1qo8sBMVXdXdWMzArgiS7VLSg)

3. Checking the version of the installed packages:

```bash
curl --version
git --version
```

[https://lh7-us.googleusercontent.com/mAb_WAJToRKUXaLZFTPm-oiCmEGs2TKeqroRRwmugPfIkXzrPQG6TTWWLx3oUEwJS47TS78g9kky8zNR6p_746w4tNUh2Wjz8chEFasz9M_Zw4A_aMk8Xr3BWMCZLmkBBsvHbz4Tqgf5yllzazwJvaI](https://lh7-us.googleusercontent.com/mAb_WAJToRKUXaLZFTPm-oiCmEGs2TKeqroRRwmugPfIkXzrPQG6TTWWLx3oUEwJS47TS78g9kky8zNR6p_746w4tNUh2Wjz8chEFasz9M_Zw4A_aMk8Xr3BWMCZLmkBBsvHbz4Tqgf5yllzazwJvaI)

**6. Run a database container in the background. Then show logs of the running container. After, access the container in interactive mode. show some SQL queries inside the container.**

1.Run a MySQL Container in the Background:

We'll pull and run a MySQL container. The -d flag runs the container in detached mode (background). We'll also set the MYSQL_ROOT_PASSWORD environment variable, which is required to  initialize the SQL

```bash
docker run -d --name mysql-container -e MYSQL_ROOT_PASSWORD=my-secret-pw mysql:latest
```

[https://lh7-us.googleusercontent.com/m8jOGgOCt5iEOtF7soPpaPyE2mn51_edb4yBrXuB7666s5KMrunANJw9Y2d_oOnF7DGzxySnKPxTnv9ygr6dXSMl6lHvNN1Vod21K5537auSyyG_Xs-fJgBn14F5-EQHm6nMlexZVSAcdlO_nr6Kkg4](https://lh7-us.googleusercontent.com/m8jOGgOCt5iEOtF7soPpaPyE2mn51_edb4yBrXuB7666s5KMrunANJw9Y2d_oOnF7DGzxySnKPxTnv9ygr6dXSMl6lHvNN1Vod21K5537auSyyG_Xs-fJgBn14F5-EQHm6nMlexZVSAcdlO_nr6Kkg4)

2.Show Logs of the Running Container:

To view the logs of the running MySQL container

```bash
docker logs mysql-container
```

[https://lh7-us.googleusercontent.com/nczKDtlIzglfpvW1DJbS6wbeaAQmLETkbKLdXtUZNF31iahEvmd31SQ1tOI7cNj10pAhte43JmzTgFnkGvlqw3fjOFVuMBmAlruFO2OFDc7xeLrErls529xNvp-eIYBlYCSGuWrkiIS-cgWSK2IQkmg](https://lh7-us.googleusercontent.com/nczKDtlIzglfpvW1DJbS6wbeaAQmLETkbKLdXtUZNF31iahEvmd31SQ1tOI7cNj10pAhte43JmzTgFnkGvlqw3fjOFVuMBmAlruFO2OFDc7xeLrErls529xNvp-eIYBlYCSGuWrkiIS-cgWSK2IQkmg)

3. Access the Container in Interactive Mode:

To interact with the MySQL server inside the container, I have used the MySQL client. By accessing the container's shell:

```bash
docker exec -it mysql-container /bin/bash
```

[https://lh7-us.googleusercontent.com/bkvifF1rO8zYHvaOBATdbrkeWOFH9ey6F1wNsp4CGxRPGi_55xdxvcewcGrDn1lAFahkTnYDKjoPdYdMpdZnDCD5LQq4BEiv8z0SPBJGbXd8qBxHEWOXjou6KMyrWJP8bM6nUWZJSbW_p1-ioMUJQqo](https://lh7-us.googleusercontent.com/bkvifF1rO8zYHvaOBATdbrkeWOFH9ey6F1wNsp4CGxRPGi_55xdxvcewcGrDn1lAFahkTnYDKjoPdYdMpdZnDCD5LQq4BEiv8z0SPBJGbXd8qBxHEWOXjou6KMyrWJP8bM6nUWZJSbW_p1-ioMUJQqo)

4.Inside the container's shell:

Access the MySQL server using the MySQL client:

```bash
mysql -uroot -pmy-secret-pw
```

[https://lh7-us.googleusercontent.com/q8O8sOKbjXzQlVx2O4jljS4lBuWBKZcz3Zlop4BqdiUImh9xi0TAGOUoJV8L_BILrzTos8YWmYgWppq7ZhRm7LNKiGi31ZuXvivRox9PqcihJB9Q9-9rG0oEFSj8G3vITd2LYEUKpRuOKzCP4s4rUv0](https://lh7-us.googleusercontent.com/q8O8sOKbjXzQlVx2O4jljS4lBuWBKZcz3Zlop4BqdiUImh9xi0TAGOUoJV8L_BILrzTos8YWmYgWppq7ZhRm7LNKiGi31ZuXvivRox9PqcihJB9Q9-9rG0oEFSj8G3vITd2LYEUKpRuOKzCP4s4rUv0)

Now i am inside the Database:

- Show Existing Database:

SHOW DATABASES;

[https://lh7-us.googleusercontent.com/2QwOzvLfZKtaB6zTVzGa6FXRf5XF8qvOHTVuTHVMdCOfhbfqPZK60HYUfiUp6t3f5zBnamI5NjKWeup2HyYQIOkDLkQBkDU0Q-2mTtBo0wysUFGANlCaf-nMl_ZaFOYl2gBnwGMwd5S-BD_Eo67i9xc](https://lh7-us.googleusercontent.com/2QwOzvLfZKtaB6zTVzGa6FXRf5XF8qvOHTVuTHVMdCOfhbfqPZK60HYUfiUp6t3f5zBnamI5NjKWeup2HyYQIOkDLkQBkDU0Q-2mTtBo0wysUFGANlCaf-nMl_ZaFOYl2gBnwGMwd5S-BD_Eo67i9xc)

- Create a new Database:

CREATE DATABASE testdb;

[https://lh7-us.googleusercontent.com/Wtawc4pMoIJduDEsCf6YWH2RWNQ-12af0TcLmRAZThZRr989O1AHrcGuSOKeV_2d4b2e8OjPyAXTZKLInX1bkUWpVkHXfXQqJubyEtyCZb5wfEQdOQR1td6lEGo_sFZ4Ef8Gg4ELtgFkQvrmZYN_gQs](https://lh7-us.googleusercontent.com/Wtawc4pMoIJduDEsCf6YWH2RWNQ-12af0TcLmRAZThZRr989O1AHrcGuSOKeV_2d4b2e8OjPyAXTZKLInX1bkUWpVkHXfXQqJubyEtyCZb5wfEQdOQR1td6lEGo_sFZ4Ef8Gg4ELtgFkQvrmZYN_gQs)

- Switch to new database:

```bash
USE testdb;
```

[https://lh7-us.googleusercontent.com/FYAzH4zl-fhS88c80DRuvawpWbWgWqApKmswXZw-IGc7G_-TumEX1YadR-cA4mGd8TJIciUPPy1ne4pzy8a1dnX0xZfkL2OtgnSWu31ceWTmHqZwoFde2Jo8AM2ZOfRrx6Oz4t9sPA7xlpjtPDRRKoE](https://lh7-us.googleusercontent.com/FYAzH4zl-fhS88c80DRuvawpWbWgWqApKmswXZw-IGc7G_-TumEX1YadR-cA4mGd8TJIciUPPy1ne4pzy8a1dnX0xZfkL2OtgnSWu31ceWTmHqZwoFde2Jo8AM2ZOfRrx6Oz4t9sPA7xlpjtPDRRKoE)

- Create a new table:

CREATE TABLE test_table (id INT, name VARCHAR(255));

[https://lh7-us.googleusercontent.com/_WZzQzX4nNFAdfY0A2aeNMybzYLTp3e3sp-0hDipIw3Ceks_Vfji6I-b1_gTb5lou-ktzyCevtbZxvAFBgjoVFlL-3Gz5cTX8peyKJKYWVs1Sx90Hv0Dj9oL_70np81OguGhzCm-zjASefKElm6rjb0](https://lh7-us.googleusercontent.com/_WZzQzX4nNFAdfY0A2aeNMybzYLTp3e3sp-0hDipIw3Ceks_Vfji6I-b1_gTb5lou-ktzyCevtbZxvAFBgjoVFlL-3Gz5cTX8peyKJKYWVs1Sx90Hv0Dj9oL_70np81OguGhzCm-zjASefKElm6rjb0)

- Insert data into table

INSERT INTO test_table (id, name) VALUES (1, 'John Doe');

[https://lh7-us.googleusercontent.com/3OZZyXvQgtHwfShKWNhY5_4SmbtTwT1HJG9bU_5y0Obq1V7ULbGSu9giYvdcGk4fg0w44RBDdYvuscr9_1m0WA3WF0tOhoImvvWfd9KgTljE6AMGVYbGlXbxYr02Lf8Kw2GzuQpepiLfrAv2uEFR3DE](https://lh7-us.googleusercontent.com/3OZZyXvQgtHwfShKWNhY5_4SmbtTwT1HJG9bU_5y0Obq1V7ULbGSu9giYvdcGk4fg0w44RBDdYvuscr9_1m0WA3WF0tOhoImvvWfd9KgTljE6AMGVYbGlXbxYr02Lf8Kw2GzuQpepiLfrAv2uEFR3DE)

- Query data from the table:

```bash
SELECT * FROM test_table;
```

[https://lh7-us.googleusercontent.com/vSX5HN7iG8T9VeTS-bMyVmScbfscyOEw0DxdVaKAfzGAHCeQKt6HJf04gHYAvPJOcz-sWJ0o4aL-B2YgNFCkhiubeGPLoHSXpwoBu8i3KQvoQIhxgLG5KX9rbfdhQAYfK6rB14YDPkpel2XI-_TtGmo](https://lh7-us.googleusercontent.com/vSX5HN7iG8T9VeTS-bMyVmScbfscyOEw0DxdVaKAfzGAHCeQKt6HJf04gHYAvPJOcz-sWJ0o4aL-B2YgNFCkhiubeGPLoHSXpwoBu8i3KQvoQIhxgLG5KX9rbfdhQAYfK6rB14YDPkpel2XI-_TtGmo)

[https://lh7-us.googleusercontent.com/KaJsMvxDLgOkPaZsuTGyugXMfDGmo7UORvms8AuUrue0qQo5Ml4fwU7SDIq1k2c6dAJqArKXbyXhPpqvlTNPBo4s8u2TUhL0esBsD2EEQwaFBfaQR9MuZGWFaWFSLeUgppXuurNr3c3hN0dic88Yd70](https://lh7-us.googleusercontent.com/KaJsMvxDLgOkPaZsuTGyugXMfDGmo7UORvms8AuUrue0qQo5Ml4fwU7SDIq1k2c6dAJqArKXbyXhPpqvlTNPBo4s8u2TUhL0esBsD2EEQwaFBfaQR9MuZGWFaWFSLeUgppXuurNr3c3hN0dic88Yd70)

**7.Push Your Image to Docker Hub:**

1.First creating a Docker Hub account. Then login into my docker account through terminal:

docker login:

[https://lh7-us.googleusercontent.com/xubGxq_RrRml7rqc77uEDlxPWzhuvqFqr-5pCTjuWPUxHLGLmuJv_fudLqUo2kp75aBuLIlSufwmWFINjTbXJfLu-g3krjdTXimxDcNA1LVejK1jp_w6K5IPlgvT_wvOFISUDAjztpCpAVhxgDGEtpU](https://lh7-us.googleusercontent.com/xubGxq_RrRml7rqc77uEDlxPWzhuvqFqr-5pCTjuWPUxHLGLmuJv_fudLqUo2kp75aBuLIlSufwmWFINjTbXJfLu-g3krjdTXimxDcNA1LVejK1jp_w6K5IPlgvT_wvOFISUDAjztpCpAVhxgDGEtpU)

2.Tag mt Image:

Before I can push your image to Docker Hub, I need to tag it with Docker Hub username. I have an image named my-custom-image that I want to push:

```bash
docker tag my-custom-ubuntu:latest razinsufian/my-custom-ubuntu:latest
```

[https://lh7-us.googleusercontent.com/qA83pShucu8GIXkqS2MQTaGUQX-BNtohBXj4z87IIbz00RWe0oFDPF29TYTTi1GgcTEq3BcobHUtywb0qh9dXqjTWXqx5pOC5OByiQlcM3jWSmm-qyqMUwsh3oCMnIDqioBwRFzHgMPWGiadM5jS37E](https://lh7-us.googleusercontent.com/qA83pShucu8GIXkqS2MQTaGUQX-BNtohBXj4z87IIbz00RWe0oFDPF29TYTTi1GgcTEq3BcobHUtywb0qh9dXqjTWXqx5pOC5OByiQlcM3jWSmm-qyqMUwsh3oCMnIDqioBwRFzHgMPWGiadM5jS37E)

[https://lh7-us.googleusercontent.com/UdNuuofmHKmlZdfe0OIYLhm5MlSYFX7XQ602pjCSIBzIFLxuDiXR7cLC1cDwW4onCeqPxjLtfMrzXsPLHC90pRTdm__DoYd-P9E_ONwOYXbttsiTRsZJW35p9DD8t-J4wzSq_BTiOrRndW_eLXwQueI](https://lh7-us.googleusercontent.com/UdNuuofmHKmlZdfe0OIYLhm5MlSYFX7XQ602pjCSIBzIFLxuDiXR7cLC1cDwW4onCeqPxjLtfMrzXsPLHC90pRTdm__DoYd-P9E_ONwOYXbttsiTRsZJW35p9DD8t-J4wzSq_BTiOrRndW_eLXwQueI)

3.Push the Image to Docker Hub:

Now, you can push the tagged image to Docker Hub

```bash
docker push razinsufian/my-custom-ubuntu:latest
```

[https://lh7-us.googleusercontent.com/V2X92niIt3bY0Awjlw9MizC5vocEyziteFxFXKyG40CdUoRND326Dlvuf91UyX9HB6uWanUwSAhIt4Rb8vYB2kMeN_8WGeDal5iy4r_DhFHg9Ve3wp0n1S9AW7DUmzwKG21woNEqARJo0Qe54NPtzig](https://lh7-us.googleusercontent.com/V2X92niIt3bY0Awjlw9MizC5vocEyziteFxFXKyG40CdUoRND326Dlvuf91UyX9HB6uWanUwSAhIt4Rb8vYB2kMeN_8WGeDal5iy4r_DhFHg9Ve3wp0n1S9AW7DUmzwKG21woNEqARJo0Qe54NPtzig)

4.verifying on Docker Hub:

[https://lh7-us.googleusercontent.com/jJsoWRkyR97bSQVTCIj2NzLmT4K35oQSl3ebmogcBBa_lsin-iwmR2Wg2_kYkPDJrVvUKU6-o3T-s32Otu8yTNdE4_QXMaRz3qCmNpYSwAdit1uh69SD7y08x2OTi72uGSFWQ8L-Ax8rQpWgt6JNO4U](https://lh7-us.googleusercontent.com/jJsoWRkyR97bSQVTCIj2NzLmT4K35oQSl3ebmogcBBa_lsin-iwmR2Wg2_kYkPDJrVvUKU6-o3T-s32Otu8yTNdE4_QXMaRz3qCmNpYSwAdit1uh69SD7y08x2OTi72uGSFWQ8L-Ax8rQpWgt6JNO4U)

[https://lh7-us.googleusercontent.com/LlA3-XxT4IkI4fpvKe3g1fgAudb5buZJqTl5oY9EjtBb2Qa3IOcWO_2VruAo4-ro6t35pMjdt3pmGVWnDHNO79Eqg_gKnpWZK_WDbTZAsJW1XjIokyXJhOp-ZZg_uNJLZHvpP_PVWpr2WOtJ_Rc1334](https://lh7-us.googleusercontent.com/LlA3-XxT4IkI4fpvKe3g1fgAudb5buZJqTl5oY9EjtBb2Qa3IOcWO_2VruAo4-ro6t35pMjdt3pmGVWnDHNO79Eqg_gKnpWZK_WDbTZAsJW1XjIokyXJhOp-ZZg_uNJLZHvpP_PVWpr2WOtJ_Rc1334)

**Step 8: Set Up Your Own Private Docker Registry**

1.Run the Registry as a Container:

Docker provides an official registry image named registry that I can use to create my own private registry. To run it:

```bash
docker run -d -p 5000:5000 --name my-private-registry registry:2
```

[https://lh7-us.googleusercontent.com/fMb7s6i6Lby-ph1bsTieoGULVcx0DMNSqU4FjxeLHH7cifTll3q9tNKzu89cM3qAr6rePGIoA9MYS_2L-GXHfOW1zp5Eca7okLfP1jhtEzrbd1-REliKzn5GPEyBnRFCXHNdOqD9L2ks2Ch2-sTMi6g](https://lh7-us.googleusercontent.com/fMb7s6i6Lby-ph1bsTieoGULVcx0DMNSqU4FjxeLHH7cifTll3q9tNKzu89cM3qAr6rePGIoA9MYS_2L-GXHfOW1zp5Eca7okLfP1jhtEzrbd1-REliKzn5GPEyBnRFCXHNdOqD9L2ks2Ch2-sTMi6g)

2.Push an Image to Your Private Registry:

Before I can push an image to your private registry, you need to tag it with the address of your private registry.

```bash
docker tag my-custom-ubuntu:latest localhost:5000/my-custom-ubuntu
```

Then, push the image:

```bash
docker push localhost:5000/my-custom-ubuntu
```

[https://lh7-us.googleusercontent.com/-n2bWuzJWuAaycL3NQyss7-DLdkZY27gobPsZ3v4EqGRISN4mt7cIrOqQ9BfEPZr5XnZM7kWrQtOx6jqh-7T6enQMtCZqIhtem6rnGqRPD58h7V2Mnd8eay4NJH1oS41ZKjrdOsf8iuDGG6nN6EXvKs](https://lh7-us.googleusercontent.com/-n2bWuzJWuAaycL3NQyss7-DLdkZY27gobPsZ3v4EqGRISN4mt7cIrOqQ9BfEPZr5XnZM7kWrQtOx6jqh-7T6enQMtCZqIhtem6rnGqRPD58h7V2Mnd8eay4NJH1oS41ZKjrdOsf8iuDGG6nN6EXvKs)

3.To ensure that my private registry works, i tried pulling the image i just pushed:

```bash
docker pull localhost:5000/my-custom-ubuntu
```

[https://lh7-us.googleusercontent.com/TGCwUU4OaZljofTetExD8a-8QAasjECgpZD94bB1mRKNTDj-pRRpjc9IXLejs06wabUIuRGYerCyI5OHgskASv-gzjRtiqJxTe9jgFaFXJzaTUdgvOlOwjTzM-Cv2pE-j2oyt65EaiqN2IAHpEBYil8](https://lh7-us.googleusercontent.com/TGCwUU4OaZljofTetExD8a-8QAasjECgpZD94bB1mRKNTDj-pRRpjc9IXLejs06wabUIuRGYerCyI5OHgskASv-gzjRtiqJxTe9jgFaFXJzaTUdgvOlOwjTzM-Cv2pE-j2oyt65EaiqN2IAHpEBYil8)

4. If i want to remove and stop the private registry container :

```bash
docker stop my-private-registry
docker rm my-private-registry
```

Note: Security Considerations additional configuration restrictions:

By default, the private registry uses HTTP, which is insecure. In a real-world scenario, I would want to set up TLS for your registry to encrypt traffic. I might also want to set up authentication to restrict who can push and pull images. And furthermore this setup is suitable for local development and testing. For production use , i would want to consider additional configurations like storage backends, securing the registry with TLS , and setting up authentication

**9. Create a small website or app with minimal functionality (Could be a simple HTML website that has a button that opens a static image/file) inside a Docker container. Then run the application (inside the container) in the background of your HOST machine in any port. Browse the website from your host machine.**

1.create a directory for my website and write a simple HTML code in it:

I have an image.jpg saved in the same directory where I have created the index.html file.

[https://lh7-us.googleusercontent.com/fg9xTcdINoiEDLPlJIwhL51MadXjrCSjsh9FJE-elLAEyFmm_Mg1U8s1ygSUCbOXJYXjdzuPCQ-7OBLj-sVVK6qfqAq6YQFFndsngf6DGyswAhFAa9ru6d3SwbYYBdVKBJbfdp-VVUkiPzyUdUadvV0](https://lh7-us.googleusercontent.com/fg9xTcdINoiEDLPlJIwhL51MadXjrCSjsh9FJE-elLAEyFmm_Mg1U8s1ygSUCbOXJYXjdzuPCQ-7OBLj-sVVK6qfqAq6YQFFndsngf6DGyswAhFAa9ru6d3SwbYYBdVKBJbfdp-VVUkiPzyUdUadvV0)

[https://lh7-us.googleusercontent.com/tqT0CsKxodhWTyYw49kH8VUkGoxXKovCRdOdk5FCZQoyZVqGIOwN96FWblIV-_p3Aq_HzDEs3TF5O-KcKmIBbeyH6iQ7BYLcKnswZn1AgNMKCGzagblrVluK9ppTFjCTe9XDdOtz_qdCAMyKVOLQPgU](https://lh7-us.googleusercontent.com/tqT0CsKxodhWTyYw49kH8VUkGoxXKovCRdOdk5FCZQoyZVqGIOwN96FWblIV-_p3Aq_HzDEs3TF5O-KcKmIBbeyH6iQ7BYLcKnswZn1AgNMKCGzagblrVluK9ppTFjCTe9XDdOtz_qdCAMyKVOLQPgU)

2.Create a Docker  File:

I will use the “nginx” image as base. Its a popular web server:

Creating Docker file:

I

```bash
nano Dockerfile
# Use the nginx image as the base
FROM nginx:alpine
# Copy our website files to the nginx default directory
COPY index.html /usr/share/nginx/html/
COPY image.jpg /usr/share/nginx/html/
```

[https://lh7-us.googleusercontent.com/JrOVNoF-oHmg7Nsy0Z64349zgFSDwc_qKaTzqTyU0TTwUkZ_SFSU554I44LkAXVjK8kSFb7A8hyGyC_WESzQe7fXL_oGTgyykG2EQxmHZrg_qxi00tW7ckDKVaiYUVqTnn-2TSnXke77SN8lBzng04Q](https://lh7-us.googleusercontent.com/JrOVNoF-oHmg7Nsy0Z64349zgFSDwc_qKaTzqTyU0TTwUkZ_SFSU554I44LkAXVjK8kSFb7A8hyGyC_WESzQe7fXL_oGTgyykG2EQxmHZrg_qxi00tW7ckDKVaiYUVqTnn-2TSnXke77SN8lBzng04Q)

3.Build the Docker Image:

Navigate to the directory containing my Dockerfile, index.html, and image.jpg. Then run:

```bash
docker build -t simple-website .
```

[https://lh7-us.googleusercontent.com/bjaT1TY_0v_tUuxXfVDpu7p545_pU9pTZ12ej0XqzMDjPU4F5vC2m0IBnKuTCsfVrealqUBjpdJM6MtAM9Up-U5fRtLt8DRTYvIDJ4P32LSfFaSeqF-DBpOrwHtrBQ2pq6meAL4krKvNPUMe7sAtEdQ](https://lh7-us.googleusercontent.com/bjaT1TY_0v_tUuxXfVDpu7p545_pU9pTZ12ej0XqzMDjPU4F5vC2m0IBnKuTCsfVrealqUBjpdJM6MtAM9Up-U5fRtLt8DRTYvIDJ4P32LSfFaSeqF-DBpOrwHtrBQ2pq6meAL4krKvNPUMe7sAtEdQ)

4. Run the Website in the Dockerfile:

```bash
docker run -d -p 8080:80 --name my-website simple-website
```

[https://lh7-us.googleusercontent.com/83njdL3QwGwEihVDPSfR_TchLcMeD-gflkB65RieyiuMD0g7jIsTDjiPm9XN9H_W1UEmEP4ehzDib9qMqSIYMB3fVoBDtSjMoCtOD3_keVlcfXlG6CsCI_NdIi_qftrqNCQfop2rAhnLizl8QqUmmWI](https://lh7-us.googleusercontent.com/83njdL3QwGwEihVDPSfR_TchLcMeD-gflkB65RieyiuMD0g7jIsTDjiPm9XN9H_W1UEmEP4ehzDib9qMqSIYMB3fVoBDtSjMoCtOD3_keVlcfXlG6CsCI_NdIi_qftrqNCQfop2rAhnLizl8QqUmmWI)

This command runs the website in a container, mapping port 8080 on your host machine to port 80 in the container.

5. Accessing the website:

If i Open a web browser and navigate to http://localhost:8080. I can see my simple website. Clicking the button will open the image.

[https://lh7-us.googleusercontent.com/JWjI4RLMO4PbEDvfl0oO0JcKFZRdl68hkFOj_X4TEg9zL2W5D_IAj7loTPBp23Ea8DsZGqQX4e2Nyv-qmK3Tl72lQ-KGcwL37R_bWkZGIC9MpiGLBRsbFp9KbJCD6m78bxv_Ly_nrkNm9u7I8QFXGb0](https://lh7-us.googleusercontent.com/JWjI4RLMO4PbEDvfl0oO0JcKFZRdl68hkFOj_X4TEg9zL2W5D_IAj7loTPBp23Ea8DsZGqQX4e2Nyv-qmK3Tl72lQ-KGcwL37R_bWkZGIC9MpiGLBRsbFp9KbJCD6m78bxv_Ly_nrkNm9u7I8QFXGb0)

[https://lh7-us.googleusercontent.com/Q3HSElsOEWGqEXcbgWpaQ8HJgv4aVSjSwY09n9DbhieK2IJVZFwwZUfQhy_LPCuuh7cBWdOL74yV3ddbAbOgS-40OBMuoMIUZrCsAQ3KQcIN0Bv-s4D6B2H-AWJ7uF_hZnOkDiELJvBXFJBH0OsYh0w](https://lh7-us.googleusercontent.com/Q3HSElsOEWGqEXcbgWpaQ8HJgv4aVSjSwY09n9DbhieK2IJVZFwwZUfQhy_LPCuuh7cBWdOL74yV3ddbAbOgS-40OBMuoMIUZrCsAQ3KQcIN0Bv-s4D6B2H-AWJ7uF_hZnOkDiELJvBXFJBH0OsYh0w)

[https://lh7-us.googleusercontent.com/Ng6LOCbT6rARfdkZz1Yli1R0leR3luGkKnJS1_Wcbo4z3cqUbAo9NYjf6ejXSy5hbdePIbdq9SFtbAOnlkSe57R2kXMxnBy28gdGag0UDkAhyrIKiZ4L9GzlQksWEAdfXcMeDphdUSYffj3w0bpoSdc](https://lh7-us.googleusercontent.com/Ng6LOCbT6rARfdkZz1Yli1R0leR3luGkKnJS1_Wcbo4z3cqUbAo9NYjf6ejXSy5hbdePIbdq9SFtbAOnlkSe57R2kXMxnBy28gdGag0UDkAhyrIKiZ4L9GzlQksWEAdfXcMeDphdUSYffj3w0bpoSdc)

**10. Migrate the new container having the application into another machine. Again run the container and browse the URL. It should work.**

1. Save the Docker Image to a File:

First, Ill need to save the Docker image to a .tar file. This process is called "exporting" the image.

```bash
docker save -o simple-website.tar simple-website
```

[https://lh7-us.googleusercontent.com/LWEqTcWehOvq76MJT-jPOuEc49gkCsF4hpVHj2B28ReV4VZ9WhYd4itlCu4aG_uX4qwVrjrZBqh2OkrQbgrPG6Y6uAa9NggVbUZHpMH43PPUaS1g0fYTsHIpBNhQ8gOhlUHcoikNl-d2FaeXWURRRow](https://lh7-us.googleusercontent.com/LWEqTcWehOvq76MJT-jPOuEc49gkCsF4hpVHj2B28ReV4VZ9WhYd4itlCu4aG_uX4qwVrjrZBqh2OkrQbgrPG6Y6uAa9NggVbUZHpMH43PPUaS1g0fYTsHIpBNhQ8gOhlUHcoikNl-d2FaeXWURRRow)

[https://lh7-us.googleusercontent.com/ZAP2DibKKcVkeKocPi_ycADojdlx4rryPdCT6XIcAExbMtfIrua82olWqY0d1EjDr-FnwaW0wDlcf-3Bm1fKkEO30aBEQYGg27H3e8ngPeSzzpPbp9TQ9fVs-Q7ZPlwMBFKbDzNPTADFD8Nor-uoBPc](https://lh7-us.googleusercontent.com/ZAP2DibKKcVkeKocPi_ycADojdlx4rryPdCT6XIcAExbMtfIrua82olWqY0d1EjDr-FnwaW0wDlcf-3Bm1fKkEO30aBEQYGg27H3e8ngPeSzzpPbp9TQ9fVs-Q7ZPlwMBFKbDzNPTADFD8Nor-uoBPc)

From a different Machine:

1.Load the Docker Image on the New Machine:

```bash
docker load -i /path/to/simple-website.tar
```

2.. Run the Docker Container on the New Machine:

```bash
docker run -d -p 8080:80 --name my-website simple-website
```

[https://lh7-us.googleusercontent.com/T__EbD0aWB_IfaG5ZJHmhuW1lb0VTpfsrlQDARqtIEkz-Utde2dDLvsl04zSs6waV1638DkAVnpjbe2fPzsjf588MNVQ19gl6vZscaXEXUmHjpQoSYleHOK0zWyVpV4vl5Pmh1AEFQ1R3U437fXCL6o](https://lh7-us.googleusercontent.com/T__EbD0aWB_IfaG5ZJHmhuW1lb0VTpfsrlQDARqtIEkz-Utde2dDLvsl04zSs6waV1638DkAVnpjbe2fPzsjf588MNVQ19gl6vZscaXEXUmHjpQoSYleHOK0zWyVpV4vl5Pmh1AEFQ1R3U437fXCL6o)

3.Access the Website:

Open a web browser on the new machine and navigate to http://localhost:8080.

[https://lh7-us.googleusercontent.com/yaSo1C6dWOs-oYIYPSjNtS4Uu2XNe5ysx3dkK8bbRSq5CxTPY5qi3xdUo16QWtiN22nHFLdL90U9gh_-0Tcp83o53RVFug5IssDgCQljluKbgXRZoyzX-RxaQA7MTO-zpZ7iFSDTDpFMQnA1CWiICO8](https://lh7-us.googleusercontent.com/yaSo1C6dWOs-oYIYPSjNtS4Uu2XNe5ysx3dkK8bbRSq5CxTPY5qi3xdUo16QWtiN22nHFLdL90U9gh_-0Tcp83o53RVFug5IssDgCQljluKbgXRZoyzX-RxaQA7MTO-zpZ7iFSDTDpFMQnA1CWiICO8)

[https://lh7-us.googleusercontent.com/ms4LkmYWEWmVAG5uMdFqS78T9jdiOIN3Xv_LDmXp6n2ft0DmZnmXkYmgACMJN3vps4W0AI7jp7fIOeBc1TmKixFz-7A3KVkOPjJUyQ9SJpFqiftg2HDPBefiMzRdPe88YbWvRw9gO3djwS2SV4fRXDQ](https://lh7-us.googleusercontent.com/ms4LkmYWEWmVAG5uMdFqS78T9jdiOIN3Xv_LDmXp6n2ft0DmZnmXkYmgACMJN3vps4W0AI7jp7fIOeBc1TmKixFz-7A3KVkOPjJUyQ9SJpFqiftg2HDPBefiMzRdPe88YbWvRw9gO3djwS2SV4fRXDQ)