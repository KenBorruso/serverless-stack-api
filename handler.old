export const hello = async (event, context) => {
  return {
    statusCode: 200,
    body: JSON.stringify({
      message: `Want to Play A Game! ${(await message({ time: 1, copy: 'Global Thermal Nuclear War!'}))}`,
    }),
  };
};

const message = ({ time, ...rest }) => new Promise((resolve, reject) =>
  setTimeout(() => {
    resolve(`${rest.copy} (Def Con 1)`);
  }, time * 1000)
);
