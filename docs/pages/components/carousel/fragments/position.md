<!--start-code-->

```js
const App = () => {
  const [activeIndex, setActiveIndex] = React.useState(2);
  return (
    <Carousel
      className="custom-slider"
      activeIndex={activeIndex}
      onSelect={index => {
        setActiveIndex(index);
      }}
    >
      <img src="https://via.placeholder.com/600x250/8f8e94/FFFFFF?text=1" height="250" />
      <img src="https://via.placeholder.com/600x250/8f8e94/FFFFFF?text=2" height="250" />
      <img src="https://via.placeholder.com/600x250/8f8e94/FFFFFF?text=3" height="250" />
      <img src="https://via.placeholder.com/600x250/8f8e94/FFFFFF?text=4" height="250" />
      <img src="https://via.placeholder.com/600x250/8f8e94/FFFFFF?text=5" height="250" />
    </Carousel>
  );
};

ReactDOM.render(<App />);
```

<!--end-code-->
