# Tailwind Tips

## General

- always remember to run `npm run watch` or `npx tailwindcss -i ./input.css -o ./css/main.css --watch` so the changes are reflected in the browser

## Classes

- `bg-gray-100` = background-color: #f7fafc
- `text-gray-700` = color: #4a5568
- `container` = max-width of 100%
- `relative` = position: relative
- `-top-6` = top: -1.5rem
- `-mt-6` = margin-top: -1.5rem
- `mx-auto` = margin-left: auto; margin-right: auto;
- `space-x-6` = margin-left: 1.5rem; margin-right: 1.5rem;
- `space-y-6` = margin-top: 1.5rem; margin-bottom: 1.5rem;
- `hidden` = display: none
- `items-center` = align-items: center
- `justify-center` = justify-content: center
- `justify-between` = justify-content: space-between
- `justify-end` = justify-content: flex-end
- `justify-around` = justify-content: space-around
- `flex` = display: flex
- `flex-1` = flex: 1, _see [Stack Overflow on Flex: 1](https://stackoverflow.com/questions/37386244/what-does-flex-1-mean)_
- `flex-grow` = flex-grow: 1, the div will grow in the same proportion as the window size
- `flex-shrink` = flex-shrink: 1, the div will shrink in the same proportion as the window size

- `flex-col-reverse` = flex-direction: column-reverse
- `md:flex` = display: flex on medium screens and up
- `hover:text-blue-500` = text-blue-500 on hover
- `rounded-full` = border-radius: 9999px
- `rounded-lg` = border-radius: 0.5rem
- `rounded` = border-radius: 0.25rem
- `w-1/2` = width: 50%
- `w-1/3` = width: 33.333333% (useful when you have 3 items)
- `w-4` = width: 1rem
- `max-w-md` = max-width: 28rem (28 \* 16 = 448px)
- `h-8` = height: 2rem
- `text-center` = text-align: center
- `text-base` = font-size: 1rem
- `leading-tight` = line-height: 1.25
- `leading-none` = line-height: 1
- `shadow-2xl` = box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25)
