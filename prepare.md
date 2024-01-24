# Prepare to Learn SYCL fast

Please do these TWO things before you attend the webinar "Learn SYCL fast."

1. Create an account (or sign-in) at [cloud.intel.com](https://cloud.intel.com). To get an account - click "Get Started" and select "Standard = Free" by clicking "Subscribe" and following the prompts to create a free account. Once you have an account, verify it works by logging in and launching a Jupyter notebook by clicking the "Launch JupyterLab" in the upper right of the web page [console.cloud.intel.com/training](https://console.cloud.intel.com/training).

2. Download a free copy of the SYCL book (Second Edition, PDF format) from [tinyurl.com/book-SYCL](https://tinyurl.com/book-SYCL).


As an alternative, you are welcome to use any system with a SYCL compiler installed.  We will not have time to help you get that setup so we recommend using the Intel Developer Cloud online as an easy way to ensure you are ready to go.

If you want to get a jump on class - you can go ahead and clone the repo, and then compile and run the program.  Here are the four commands to do that (assuming Linux and a standard Intel tools installation):

```bash
git clone --recursive --branch sc23 https://github.com/codeplaysoftware/syclacademy.git
cd syclacademy/Code_Exercises/Exercise_01_Big_Hello_SYCL/
source /opt/intel/oneapi/setvars.sh
cp ../Images/goldfish.png .
icpx -fsycl solution.cpp
./a.out goldfish.png
```
