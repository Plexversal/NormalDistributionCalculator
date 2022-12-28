# Standard Normal Distribution probability calculator

![905e6363-dda9-44ea-af79-51fc41b0fb74](https://user-images.githubusercontent.com/47725871/209799605-e68f4936-f43b-4c14-9fd8-401d548d337f.png)


This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

Standard normal distribution calculator made with P5.js and Next.js. Used for calculating cumulative values of X on the standard normal graph with a mean of 0 and a standard deviation of 1.

The area calculated is using the definite integral of the normal distribution function which is equal to the Gauss error function taking in the value of x/sqrt(2)+1 and that all over 2.

The Gauss error function is non-elementary but there are approximations available to use, this project uses one from [Abramowitz and Stegun](https://en.wikipedia.org/wiki/Error_function#Approximation_with_elementary_functions).

The math related can be found in the index of 'pages' of this project.

## To run this project

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

